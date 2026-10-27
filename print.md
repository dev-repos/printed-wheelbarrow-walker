# Printed wheelbarrow walker — print sheet

Generated from the parametric model.

**Settings for every part:** PLA, 0.4 mm nozzle, 0.2 mm layers, 3 walls, 20 % infill, no brim, bed ≥ 180×180 mm. Each part has its own colour so it's easy to spot on the bench and in the video (any colours work).

| Part | File | Qty | Colour | Size (mm) | Orientation | Supports | Est. g each |
|---|---|---|---|---|---|---|---|
| P01 Crank | `stl/P01_crank.stl` | 2 | #FF7A00 | 18.4 × 12.0 × 14.0 | flat, pin up | no | 0.6 |
| P02 Leg | `stl/P02_leg.stl` | 2 | #1E88E5 | 54.0 × 94.0 × 4.0 | flat | no | 2.8 |
| P03 Wheel | `stl/P03_wheel.stl` | 2 | #E53935 | 65.0 × 65.0 × 8.0 | flat | no | 7.5 |
| P04 Motor cradle | `stl/P04_cradle.stl` | 1 | #7E57C2 | 26.3 × 29.0 × 46.0 | upright, slots down | no (8 mm slot arch bridges; 3 mm boss overhang — add support only if it sags) | 4.8 |
| P05 Hip peg | `stl/P05_hip_peg.stl` | 2 | #F5F5F5 | 8.0 × 8.0 × 16.1 | head down | no | 0.2 |
| P06 Pin cap | `stl/P06_pin_cap.stl` | 2 | #212121 | 8.0 × 8.0 × 2.0 | flat | no | 0.0 |
| P07 Shoulder yoke | `stl/P07_yoke.stl` | 1 | #43A047 | 22.9 × 59.4 × 16.0 | upside down, brackets on the bed | no | 2.2 |
| P08 Arm | `stl/P08_arm.stl` | 2 | #00BCD4 | 63.9 × 8.0 × 4.0 | flat | no | 1.1 |
| P09 Barrow rail | `stl/P09_rail.stl` | 2 | #EC407A | 109.0 × 10.0 × 4.0 | flat | no | 2.1 |
| P10 Tray | `stl/P10_tray.stl` | 1 | #FDD835 | 75.0 × 88.0 × 37.0 | upside down, rim on the bed | no (walls lean ≤ 25°) | 12.7 |
| P11 Motor clip | `stl/P11_motor_clip.stl` | 1 | #8D6E63 | 30.5 × 23.1 × 8.0 | plate down | no | 1.1 |

Total ≈ 49 g PLA (estimate; your slicer's number wins).

## Fits (already in the models)

- Crank on the TT motor shaft: double-D bore 5.4 + 0.1 mm, flats 3.7 + 0.1 mm — snug push fit.
- Hip pegs press into the cradle bosses (+0.1 mm); legs swing on them (+0.5 mm).
- Pins and pegs have a 0.6 mm lead-in chamfer so they start straight and slide in smoothly.
- Skewer holes are 3.1 mm (snug, glue the stubs); wheel holes are 3.5 mm so the wheels spin free.

## Buy (not printed, not cut) — same for both builds

| Item | Qty | Notes |
|---|---|---|
| TT gear motor, **double shaft**, 3–6 V, 1:48 (yellow) | 1 | about 65 mm long, gearbox 37.5 × 22 × 18.8 mm, shaft 12 mm from the gearbox end |
| 2×AA battery holder **with on/off switch** and leads | 1 | about 58 × 31 × 15 mm |
| AA batteries | 2 | |
| Short hook-up wire (if the motor has no leads) | 20 cm | solder or twist + tape (grown-up) |
| 3 mm bamboo skewer | 1 | axle ~97 mm, 4 pin stubs ~10 mm |
| Ping-pong ball + red bottle cap | 1 each | head and hat |
| Hot glue (grown-up), double-sided tape, sandpaper 240 | — | |

## Attaching the bought parts

- **Motor:** shaft sideways, can up. Slide the cradle (P04) up over it from below until the gearbox shoulder stops against the inner ledge — the shaft is then exactly at the top of both slots. Snap the motor clip (P11) on underneath; the motor's end tab goes through its hole. Nothing is glued, so the motor can come out again.
- **Battery holder:** drops into the pocket between the two ribs in the tray (P10); a strip of double-sided tape stops it rattling. Switch facing up so you can reach it.
- **Wiring:** holder leads to the two motor terminals on top of the can (grown-up solders, or twist and tape). Run the wires down the back of the robot and over the tray's rear wall. If it walks backward, swap the two wires.

Cardboard build: same bought parts; the cardboard clip (P11) is glued to the cradle only on one side so it can still open, and the holder is held with double-sided tape.

Checked: mechanism `check.py` OK; every part manifold and on the bed; assembled at 8 crank angles with no clashes (none).
