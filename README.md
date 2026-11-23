# Splat to Game: free beta

Turn a Gaussian splat (.ply) of a single object into a game-ready mesh pack: GLB with a baked colour texture,
LOD0/1/2, a collision mesh, and a PASS/WARN/FAIL report for Unity, Unreal or Godot. Runs locally on your own
NVIDIA GPU; your splats never leave your PC.

**Beta limits:** Draft quality only, single objects (not scenes), Windows + NVIDIA GPU with 16 GB.
On first run the app downloads its AI parts (about 12 GB: PyTorch, ComfyUI, the Pixal3D models including Meta
DINOv3, whose licence you are asked to accept).

## Download
See [Releases](../../releases). The installer is unsigned for now, so Windows SmartScreen will say
"Windows protected your PC": click **More info**, then **Run anyway**.

SHA-256 of SplatToGame-Setup-0.2.0.exe: `226daabad88dfdb3aa6360c1c1a57d1be8e6a6e80833d4b7525bca9f24dbdc83`

## Licences
Third-party licences: THIRD_PARTY_LICENSES.txt (Blender GPL, ComfyUI GPLv3, PyTorch BSD, Python PSF and others).
Meta DINOv3 licence: DINOv3_LICENSE.md.

Enki Labs UK Ltd.
