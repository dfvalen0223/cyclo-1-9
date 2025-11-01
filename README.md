# Cycloidal Gearbox 1:9 — FreeCAD models

**Objective:** Single-step cycloidal gearbox, 1:9 ratio, variants with different displacement coefficients `x`. It uses an ACROPIX 6902ZZ bearing and a Pololu N20 1000:1 motor.

## Contents
- `cad/freecad/`: `.FCStd` sources per variant (`x`).
- `exports/`: STL for printing.
- `variants/variants.csv`: table with `variant, x, ratio, To_Nm, measurements`.
- `scripts/`: macros for exporting and generating profiles.

## FreeCAD Version
- FreeCAD: 1.0.0
- Workbenches: (TechDraw, Part, Part Design)

## How to export
1. Open `.FCStd`.




2. `scripts/export_step.py` generates STEP and STL files in `exports/`.

## Variants
- Naming convention: `reducer_x-0.1339.FCStd` (1:9 ratio).

- Complete table in `variants/variants.csv`.

## License
- Hardware (CAD models): **CERN-OHL-S v2** (copyleft).
- Code/macros: **MIT**.
- Documentation (README, PDFs): **CC BY 4.0**.

See the `LICENSES/` folder.
