# ⚙️ Print Settings for Alembic

The structural components of the **Alembic Toolhead** sit directly above the hotend inside an enclosed build chamber and clamp pressurized pneumatic seals under continuous bolt tension. Because of this thermal and mechanical environment, parts must be printed in rigid, high-temperature engineering plastics—we strongly recommend **ABS, ASA, or PC (Polycarbonate)**.

> [!CAUTION]
> **Material Warning (No PLA or PETG)**
> Do **not** print structural toolhead parts in PLA or PETG. Radiant heat from the hotend and stepper motor will cause PLA and PETG to soften, warp, and lose clamping pressure on the internal O-rings, resulting in air leaks and toolhead failure.

---

## Slicer Recommendations (0.4mm Nozzle)

Below are the baseline parameters tuned to balance low toolhead mass, airtight layer bonding, and structural stiffness:

| Parameter | Recommended Value |
| :--- | :--- |
| **Material** | ABS, ASA, or PC (CF/GF-filled variants also work well with a hardened nozzle) |
| **Layer Height** | 0.20mm |
| **Extrusion Width** | 0.40mm – 0.45mm |
| **Wall Perimeters** | 4 (minimum) |
| **Top / Bottom Solid Layers** | 5 Top / 5 Bottom |
| **Infill Type** | Grid, Gyroid, or Rectilinear |
| **Infill Percentage** | 40% (minimum) |
| **Supports** | None required (parts are designed for support-free printing) |

> [!NOTE]
> **Tubing Bending Jig Settings (`Bend_Tool_Base.stl` & `Bend_Tool_Lever.stl`)**
> Print both bending jig parts with at least **4 wall perimeters and 40%+ infill** so the forming channels do not flex or ovalize when bending the 5mm aluminum cooling tubes.

---

### Pro-Tips

- **Shrinkage & Flow Calibration:** Because the `Manifold_Frame` and `Lower_Body` house internal air channels, 9x2mm O-ring grooves, and 5mm aluminum tubes, dimensional accuracy is critical for an airtight seal. If printing in ABS or ASA, calibrate your extrusion multiplier and shrinkage compensation first—parts that require excessive force to seat the aluminum tubes or O-rings indicate over-extrusion or uncalibrated shrinkage. You can print a standard [20mm calibration cube](https://github.com/Alchemical-3D/Extras) to dial in scaling before printing the toolhead.
- **Layer Adhesion & Cooling:** Use minimal part cooling appropriate for your enclosure temperature so adjacent layers fuse completely. Strong interlayer adhesion prevents the manifold from delaminating when tightening the 65mm vertical tie-bolts.

Once your parts are printed and inspected, cross-check your hardware against the [Bill of Materials](BOM.md) and proceed to the [Assembly Guide](Assembly_Guide.md).

***
*Documentation prepared with AI editorial assistance • Engineered & maintained by Alchemical-3D.*
