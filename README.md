High-Torque NEMA 23 Planetary Gearbox (25:1)

A high-precision, 3D-printable 25:1 planetary gearbox designed for NEMA 23 stepper motors. This project features a dual-stage reduction and an integrated custom ball-race bearing system to handle high axial loads—ideal for high-resolution tracking applications like the Printonian Telescope or robotic actuators.
🛠 Project Overview

Standard 3D-printed gearboxes often struggle with axial load and backlash. This design addresses those issues by:

    Dual-Stage 5:1 Reduction: Achieving a total 25:1 ratio for massive torque and sub-degree resolution.

    Integrated 8mm Ball Race: A custom-designed thrust bearing using 25x 8mm steel balls to ensure smooth rotation under heavy weight.

    Hybrid Construction: Optimized for a mix of 3D-printed gears and standardized steel hardware (SKF bearings and M4/M5 fasteners).

📦 Bill of Materials (BOM)
⚙️ Mechanical Components
Item	Part Number/Spec	Quantity	Purpose
Primary Bearing	SKF 608-2ZZ	2	Main axis support
Planet Bearings	SKF 625-2Z	2	Internal gear stability
Thrust Bearings	8mm Steel Balls	25	Custom ball-race assembly
Main Axis	Nema2356_axis	1	Power transfer
🔩 Fasteners

    M5x25mm SHCS: 10x (Main housing assembly)

    M4x16mm BHSF: 4x (Component mounting)

    M5x25mm BHSF: 3x (Secondary plate attachment)

    M4 Hex Nuts: 4x (Retention)

🖨 Recommended Print Settings

To ensure gear longevity and heat resistance (especially near the NEMA 23 motor):

    Material: ASA or PETG (Highly recommended for the Sun gear and Motor Plate).

    Walls: 6 perimeters (for tooth strength).

    Infill: 40% Gyroid.

    Layer Height: 0.15mm (for smooth gear mesh).

    Horizontal Expansion: Calibrate your printer to ±0.02mm to minimize backlash.

🔧 Assembly Sequence

    Motor Prep: Press-fit the Sun gear onto the NEMA 23 shaft. Secure with a set screw if applicable.

    First Stage: Assemble the first three planets onto the carrier using the SKF 625-2Z bearings.

    The Race: Clean the 8mm steel balls and apply a thin layer of lithium grease to the printed race. Carefully place all 25 balls into the channel.

    Final Stack: Layer the second stage carrier and the top housing.

    Closure: Use the M5x25mm bolts in a star pattern to ensure even pressure across the planetary gears.

📐 Calculated Performance

With a standard 1.8° NEMA 23 motor:

    Steps per Revolution: 40,000 (at 1/16 microstepping).

    Resolution: 0.009° per step.

    Mechanical Advantage: 25x Input Torque (minus efficiency losses).
