# 📋 Bill of Materials (BOM)

This list contains all the 3D-printed components, fasteners, pneumatic hardware, and electronics required to assemble the **Alembic Toolhead**.

> [!NOTE]
> **Affiliate Links**
> This document contains affiliate links. Sourcing your parts through these links helps support the continued development of Alchemical-3D projects at no additional cost to you, and in some cases provides a discount!

*Note: Quantities for some hardware fasteners (e.g., M3 screws, heat-set inserts) are estimates and may vary slightly based on your specific A3DP FXD extruder, hotend, and carriage configuration. Keeping spare fasteners and O-rings on hand is always recommended.*

---

## 1. Printed Parts

Print these components using the material and slicer guidelines specified in the [Print Settings](Print_Settings.md) page.

| Part File Name | Qty | Description / Notes |
| :--- | :---: | :--- |
| `Lower_Body.stl` | 1 | Main lower chassis holding the aluminum cooling tubes and grub screws. |
| `Manifold_Frame.stl` | 1 | Central pneumatic manifold routing pressurized air to the lower body. |
| `Fan_Baffle_Takoto.stl` *or* `Fan_Baffle_Dragon.stl` | 1 | Hotend cooling duct and toolless 2510 fan housing (print the file matching your hotend). |
| `Chainflex_Clamp_Main.stl` | 1 | Outer clamp half for securing the electrical/pneumatic umbilical bundle. |
| `Chainflex_Clamp_Base.stl` | 1 | Inner base support for the umbilical strain relief. |
| `Pnuematic_Strain_Relief.stl` | 1 | Upper pneumatic tube strain-relief block *(note filename spelling in `STL_Files/`)*. |
| `Intake_6mmOD.stl` | 1 | Upper pneumatic intake block (`PC4-M10` port). |
| `Sensor_Retainer.stl` *or* `Sensor_Retainer_Dragon-MZE.stl` | 1 | Retains the BDsensor probe—choose Takoto (`Sensor_Retainer.stl`) or Dragon/MZE variant. *(Optional)* |
| `BD_Mod_Clamp.stl` | 1 | Clamp for securing the BDsensor module. *(Optional)* |
| `Shim_06mm_BDsensor.stl` *or* `Shim_56_BDsensor_Dragon-MZE.stl` | 1 | Offset shim for dialing in nozzle-to-BDsensor height—choose the matching height shim from [`STL_Files/`](STL_Files) for your hotend stack. *(Optional)* |
| `Bend_Tool_Base.stl` | 1 | Forming jig base for bending the 5mm OD aluminum cooling tubes without kinking. |
| `Bend_Tool_Lever.stl` | 1 | Forming lever used with `Bend_Tool_Base.stl` to wrap the aluminum tubes around the die radius. |

---

## 2. Fasteners & Physical Hardware

| Item | Qty (Est.) | Description |
| :--- | :---: | :--- |
| **[M3 Heat Set Inserts](https://kb-3d.com/store/inserts-fasteners-adhesives/278-brass-heat-set-threaded-insert-for-plastic-m3x5x4mm.html?affp=6182)** | ~4 | Standard Voron-spec M3x5x4mm brass inserts (2 installed in the Intake and 2 in the Strain Relief block). |
| **[M3 x 65mm SHCS](https://amzn.to/4vQRHtp)** | ~2 | Long vertical SHCS tie-bolts passing through the lower body, manifold, and intake to clamp the pneumatic stack. |
| **[M3 x 8mm SHCS](https://amzn.to/3QIvw8G)** | ~8 | General assembly SHCS screws (4 for the carriage mount—2 front, 2 rear sides—and 2 for the Chainflex clamp, plus spares). |
| **[M3 x 20mm Cap/Button Head](https://amzn.to/3QIvw8G)** | ~2 | Secures the pneumatic strain relief block to the intake assembly. |
| **[M3 x 24mm BHCS](https://amzn.to/3QIvw8G)** | ~2 | Passes through the front of the fan baffle and manifold into the carriage. |
| **[M3 Grub Screws](https://kb-3d.com/store/inserts-fasteners-adhesives/870-alloy-set-screw-m3-x-05-x-4mm-cup-point-1656776837904.html?affp=6182)** | ~2 | M3x4mm set screws to lock the 5mm aluminum cooling tubes inside the lower body. |
| **[Aluminum Tube 5mm OD x 3mm ID](https://amzn.to/4ntsNw5)** | 2 | `5mm OD x 3mm ID` aluminum tubing (cut to ~55mm length per side prior to forming in the bending jig). |
| **[O-Ring 9x2 (23/64" x 5/64")](https://amzn.to/4d411CT)** | 2 | Seals the pneumatic air path (1 under the `PC4-M10` fitting on top of the Intake, and 1 between the Intake and Manifold Frame). |
| **[PTFE Bowden Fitting (PC4-M10)](https://kb-3d.com/store/e3d/313-e3d-threaded-bowden-coupling-175-1644689893776.html?affp=6182)** | 1 | Straight-through PC4-M10 pneumatic fitting threading into the top of the intake. |
| **[Part Cooling Pneumatic Tube](https://amzn.to/4cFbqoF)** | 1 | `6mm OD x 4mm ID` pneumatic airline and push-to-connect fittings from your air source (e.g., Pneuma). |
| **[M2 Heat Set Inserts](https://kb-3d.com/store/inserts-fasteners-adhesives/602-brass-heat-set-threaded-insert-for-plastic-m2x35x3mm-1656874172023.html?affp=6182)** | ~2 | Standard M2x3.5x3mm brass inserts for the BDsensor mount only. *(Optional)* |
| **[M2 x 10mm BHCS](https://amzn.to/4vUwuis)** | ~1 | Secures the BDsensor retainer and clamp. *(Optional)* |
| **[M2 x 8mm BHCS](https://amzn.to/4vUwuis)** | ~1 | Secures the BDsensor retainer and clamp. *(Optional)* |

---

## 3. Electronics & Motion Hardware

| Item | Qty | Description |
| :--- | :---: | :--- |
| **[Extruder](https://kb-3d.com/store/extruders-hotends/9466-a3dp-fxd-fixed-gear-extruder-v11-1776099901694.html?affp=6182)** | 1 | A3DP FXD Fixed-Gear Extruder (supports NEMA 14 pancake steppers). |
| **[Hotend](https://advanced3dprinting.com/products/takoto-hotend?_pos=3&_sid=1122f6a8f&_ss=r)** | 1 | Takoto or Dragon Hotend. |
| **[Hotend Cooling Fan](https://kb-3d.com/store/fans/3684-2510-ball-bearing-cooling-fan-24v-1740693669311.html?affp=6182)** | 1 | 2510 ball-bearing axial fan (24V) for the Takoto/Dragon heatsink. |
| **[Filament Umbilical Tube](https://kb-3d.com/store/hardware/238-ptfe-tubing-3125-id-4762-od-black-per-foot.html?affp=6182)** | 1 | Standard PTFE Bowden guide tube. |
| **[CAN / Wiring Umbilical](https://kb-3d.com/store/wiring-connectors/792-igus-chainflex-control-cable-cf9-05-04-per-foot-1674670790036.html?affp=6182)** | 1 | Igus Chainflex CF9.05.04 motion-rated control cable. |
| **[Bed Probe (Optional)](https://www.pandapi3d.com/product-page/bed-distance-sensorm)** | 1 | PandaPi BDsensor eddy-current bed distance sensor. |

> [!IMPORTANT]
> **Part Flexibility & CAD Modifications**
> Veering from the listed hardware may require adapting the printed geometry to fit your specific components. Full **STEP files** are provided in the [`STEP_Files/`](STEP_Files) directory (including COTS fitting reference models `Alembic_Toolhead_V201 - PC4-M10 Bowden Pass-Through.step` and `Alembic_Toolhead_V201 - Pnuematic_Fitting_6mmOD.step`) to make custom modifications straightforward. If you need help or want to request hardware support, reach out in the [Alchemical-3D Discord](https://discord.gg/aE49DW2xXe)!

***
*Documentation prepared with AI editorial assistance • Engineered & maintained by Alchemical-3D.*
