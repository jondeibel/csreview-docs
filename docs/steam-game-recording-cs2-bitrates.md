# Steam Game Recording Exact Bitrate Table for CS2 (NVIDIA & AMD)

Full interactive guide: https://csreview.app/steam-game-recording-cs2-settings

Steam Game Recording does not expose a custom bitrate slider or constant-quality mode. It chooses a fixed average bitrate from a hardcoded table keyed strictly on your game's vertical render height.

## Steam Hardcoded Bitrate Table by Vertical Render Height

| Steam Preset | Under 1080p (e.g. 1280x960) | 1080p (1920x1080 / 1440x1080) | 1440p (2560x1440 / 1920x1440) | 2160p (4K) |
| --- | --- | --- | --- | --- |
| **Low** | 3.75 Mbps (~1.7 GB/hr) | 6.0 Mbps (~2.7 GB/hr) | 11.0 Mbps (~4.9 GB/hr) | 19.0 Mbps (~8.5 GB/hr) |
| **Medium** | 5.6 Mbps (~2.5 GB/hr) | 9.0 Mbps (~4.0 GB/hr) | 16.5 Mbps (~7.4 GB/hr) | 28.5 Mbps (~12.8 GB/hr) |
| **High (default)** | 7.5 Mbps (~3.4 GB/hr) | 12.0 Mbps (~5.4 GB/hr) | 22.0 Mbps (~9.9 GB/hr) | 38.0 Mbps (~17.1 GB/hr) |
| **Ultra** | 12.0 Mbps (~5.4 GB/hr) | 24.0 Mbps (~10.8 GB/hr) | 32.0 Mbps (~14.4 GB/hr) | 50.0 Mbps (~22.5 GB/hr) |

## Recommended CS2 Settings

1. **Record in Background:** 90 to 120 minute rolling buffer (holds a full match plus overtime).
2. **Quality Preset:** High for 1080p or 1280x960 (4:3); Medium for 1440p (including 1920x1440 stretched, which still falls in the 1440p column at 22 Mbps on High and drops 25% in file size on Medium).
3. **GPU Hardware Encoding:** ON (uses dedicated NVIDIA NVENC or AMD AMF/VCN media silicon off to the side of 3D shaders). Do not run a second live recorder (OBS, Medal, Outplayed) at the same time.
4. **HEVC (H.265):** ON for NVIDIA GTX 10-series / RTX 20+ and AMD RX 5000+ GPUs for sharper HUD text and cleaner smoke gradients at identical file sizes.
5. **Framerate:** Keep at 60 fps. Steam's bitrate table has no framerate multiplier, so dropping to 30 fps saves zero disk space while halving visibility on fast flicks.
6. **Audio:** Turn on Game Audio and Record Microphone (matching the input device CS2 uses).

To automatically extract every finished match out of Steam's rolling buffer, sync it with the 2D/3D demo, and cap storage automatically (100 GB default), see [CSReview](https://csreview.app).
