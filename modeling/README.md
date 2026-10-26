# Blender files

| File | Contents |
| --- | --- |
| [01-figurine.blend](01-figurine.blend) | Figurine, with four color regions |
| [02-base-mvkaran.blend](02-base-mvkaran.blend) | Base with pegs and `mvkaran` lettering |
| [03-base-plain.blend](03-base-plain.blend) | Plain base with pegs |
| [Codex-pet-v2.blend](Codex-pet-v2.blend) | Assembled figurine and named base |
| [Codex-pet-v2-plain-base.blend](Codex-pet-v2-plain-base.blend) | Assembled figurine and plain base |

Saved in Blender 5.2.1 LTS.

## Editing and exporting

- Printable objects are in `PRINT BODY` and `PRINT BASE`.
- `STUDIO - not printable` contains the camera, lights and floor. Exclude it when exporting.
- Object scale is **0.001**: mesh coordinates are in millimeters and the scene uses meters. Keep the scale and check dimensions after export.
- Individual pieces sit at Z=0. The assembled scenes show how the parts fit together.

Use the [Bambu projects](../print-projects/) for printing, or the [geometry-only 3MFs](../geometry/) to set up another slicer. See the [print guide](../docs/PRINTING.md) for dimensions and fit.
