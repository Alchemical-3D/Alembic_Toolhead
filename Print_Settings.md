# Print Settings for Alembic

The structural parts of the Alembic Toolhead should be printed in rigid, temperature-resistant materials. We strongly recommend **ABS, ASA, or PC** to withstand the thermal environment near the hotend and carriage.

## Slicer Recommendations (0.4mm Nozzle)

Below are the suggested values for a perfectly balanced print between weight, strength, and print duration.

| Parameter | Recommended Value |
| --- | --- |
| **Layer Height** | 0.2mm |
| **Extrusion Width** | 0.4mm - 0.45mm |
| **Wall Perimeters** | 4 (minimum) |
| **Top / Bottom Solid Layers** | 5 Top / 5 Bottom |
| **Infill Type** | Grid, Gyroid, or Rectilinear |
| **Infill Percentage** | 40% |
| **Supports** | Yes, where indicated (or generally on build plate only, depending on orientation). Slicer auto-supports may be needed on certain overhangs. |

### Additional Pro-Tips
- **Shrinkage Compensation:** If using ABS/ASA, remember to ensure your filament flow and scaling are dialed in so bearings and screws fit snugly without cracking the plastic.
- **Cooling:** Depending on your current printer, use minimal part cooling to ensure excellent layer adhesion for structural integrity.

Once you have your parts printed, proceed to the [Assembly Guide](Assembly_Guide.md) and check your [Bill of Materials](BOM.md) for required hardware.
