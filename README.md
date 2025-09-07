# microstrip-patch-antenna
Design and simulation of a Microstripline Rectangular Patch Antenna using CST Studio Suite
> **Note:** The patch and feedline dimensions mentioned here are based on standard design equations for a 2.4 GHz antenna.
> The actual dimensions used in the CST simulation may slightly differ, as fine-tuning was done during the design process.
Example Parameters (2.4 GHz, FR-4 Substrate)

Substrate: FR-4 (εr = 4.4, h = 1.6 mm)

Ground Plane: Copper, size ~ (W+6h) × (L+6h)

Patch: Copper, thickness ~ 0.035 mm

Feed: Microstripline (width calculated for 50Ω using LineCalc in CST or formula)

From calculations:

Patch Width (W) ≈ 38 mm

Patch Length (L) ≈ 29 mm

Feedline Width ≈ 3 mm

CST Modeling Steps

Create Substrate:

Draw box → Material: FR-4 → Size (W+extra, L+extra, h).

Ground Plane:

Draw sheet (metal) → Place at bottom of substrate.

Patch:

Draw sheet (metal) → Place on top of substrate → Dimensions (W × L).

Feedline:

Draw microstripline → Width = ~3 mm, length extending out.

Excite using Waveguide Port at end of feed.

Boundary Conditions:

Open (add space).

Simulation:

Frequency range 2–3 GHz.

Run frequency domain solver.
Results to Check

S11 (Return Loss): Should be ≤ –10 dB at 2.4 GHz.

VSWR: ~1–2.

Radiation Pattern: Broadside (in Z-direction).

Gain: Typically 5–7 dBi for patch.
