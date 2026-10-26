# Printing and assembly

## Setup

Prepared with Bambu Studio 2.8.2.61 for a P1S, 0.4 mm nozzle, textured PEI plate and AMS.

1. Open the figurine and your chosen base from [print-projects](../print-projects/) as separate projects in Bambu Studio.
2. Check the printer, plate and filament profiles. Keep both parts at **100% scale**.
3. Slice each project. Print the figurine upright and the base flat, with pegs pointing up.
4. Map the materials to your AMS slots before sending the job. The named base uses material IDs **2 and 3**; the plain base uses **2** only.

## Figurine

| Setting | Value |
| --- | --- |
| Layer height | 0.16 mm, with 0.12 and 0.08 mm sections; 0.20 mm first layer |
| Crown | 0.08 mm above approximately 94.2 mm |
| Walls | 3 |
| Infill | 5% straight-line (`zig-zag`) |
| Top shell | 8 layers; 1.2 mm minimum thickness |
| Supports | Automatic tree, 2 top interface layers, 0.24 mm top Z distance |
| Seams | Toward the rear |
| Prime tower | Enabled |

Support blockers keep the foot sockets clear. The eyes and chest symbol print as part of the figurine using the assigned colors.

Slice estimate: **15 h 33 min, 237.67 g**, with 324 filament changes and 746 layers.

## Bases

Both bases use these settings:

| Setting | Value |
| --- | --- |
| Layer height | 0.16 mm; 0.20 mm first layer |
| Walls | 5 |
| Infill | 60% gyroid |
| Top / bottom shells | 6 layers each |
| Supports / brim | Off |
| Seams | Rear corner of the base and backs of the pegs |

The higher infill gives the base weight. These settings are object overrides; check the **Objects** tab rather than the global profile.

| Base | Materials | Prime tower | Estimated time | Total filament |
| --- | --- | --- | --- | --- |
| Named | Dark Blue base, Ice Blue lettering | On | 4 h 51 min | 71.98 g |
| Plain | Dark Blue | Off | 3 h 27 min | 46.94 g |

Both slices have 128 layers. The named base has 38 color changes; the plain base has none. The plain base has been sliced but not yet printed.

The footprint is 78 × 47 mm and the base is 14.5 mm tall, plus 6 mm pegs. The plain version has a smooth front and the same pegs as the named version.

## Joint and assembly

| Feature | Model dimension |
| --- | --- |
| Peg diameter | 5.00 mm |
| Peg height above base | 6.00 mm |
| Peg center spacing | 23.00 mm |
| Round socket diameter | 5.30 mm |
| Round socket entry chamfer | First 0.30 mm above the sole |
| Round socket straight section | From 0.30 to 6.60 mm above the sole |
| Other socket | Elongated and tapered; dimensions below |

Lower the figurine onto the pegs until its soles rest on the base. The joint is removable and slightly loose. Hold the base when carrying the model; grip near the feet when separating the parts.

### Elongated socket

The elongated socket is wider near the entrance, so the two sockets can feel different.

| Depth above sole | Opening, X × Y |
| --- | --- |
| 1.0 mm | 6.109 × 5.809 mm |
| 3.0 mm | 5.927 × 5.627 mm |
| 5.0 mm | 5.745 × 5.445 mm |
| 6.6 mm | 5.600 × 5.300 mm |

These are approximate mesh measurements. Printed holes also depend on calibration and seam placement. Both socket roofs taper above the peg space to reduce the need for internal supports.

## Surface finish

Print upright for a cleaner face and less support contact on the back of the head. Supports under the head and arms still need cleanup. Layer lines will remain around curved surfaces.
