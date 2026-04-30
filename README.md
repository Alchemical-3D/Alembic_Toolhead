<div align="center">

# 🧪 Alembic Toolhead

[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)
[![Cooling](https://img.shields.io/badge/Cooling-Compressed%20Air-blue)](#)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-Alchemical--3D-purple)](#)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-A3DP-orange)](#)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE.md)

A highly specialized, ultra-lightweight toolhead designed for the Alchemical-3D ecosystem and A3DP gantry kits. Alembic replaces bulky fans with a rigid, compressed-air cooling architecture.  This toolhead is currently in the Alpha phase of development with working models.  Please review our **[Alpha State & Development Direction](ALPHA_&_DIRECTION.md)** document for more details on support, the project roadmap, and how to provide feedback.



<p align="center">
  <img src="Images/full_images/alembic_angle_down.png" width="45%" alt="Alembic Angle Down" />
  &nbsp;
  <img src="Images/full_images/alembic_angle_up.png" width="45%" alt="Alembic Angle Up" />
</p>

**[Bill of Materials](BOM.md)** &nbsp;•&nbsp; **[Assembly Guide](Assembly_Guide.md)** &nbsp;•&nbsp; **[Print Settings](Print_Settings.md)**

</div>

<br>

---

## 🌬️ The Philosophy of Alembic

Alembic differentiates itself by dropping traditional bulky 4010 or 5015 part cooling fans entirely. Instead, it utilizes remote compressed air delivered through a pneumatic tube for high-performance part cooling. 

By integrating aluminum tubing directly into the structural integrity of the carriage, Alembic achieves a design that is incredibly lightweight, surprisingly rigid, and maximally compact—offering unobstructed visibility of the nozzle during layering.

> [!NOTE]
> **Sledgehammer vs. Scalpel**<br>
> *"While traditional systems focus on brute-forcing CFM to wash the area with ambient cooling, Alembic focuses on exact air placement and extreme air speed to achieve superior results. Where CPAP configs are the sledgehammer... Alembic is the scalpel."*


## ✨ Key Specifications & Features

- **Primary Extruder Support:** Initial geometry tailored for the **A3DP FXD**, but is being adopted for a wide range of support.
- **Standard Hotend:** Pre-configured for the **Takoto Hotend** but is being adopted for a wide range of support.
- **Part Cooling:** High-speed compressed air via a `6mm OD x 4mm ID` pneumatic tube pipeline. 
- **Hotend Cooling:** Powered efficiently by a single lightweight **2510 fan** *(for now...)*.
- **Umbilical Management:** Features dedicated, secure routing channels for **Chainflex (CAN/USB wiring)**, the primary pneumatic airline, and the PTFE filament tube.

---

## 📚 Documentation Index

Everything you need to successfully replicate Alembic on your own machine:

| Category | Description |
| :--- | :--- |
| 📋 **[Bill of Materials (BOM)](BOM.md)** | The comprehensive checklist of printed parts, heat sets, hardware, and pneumatics needed. |
| 🛠️ **[Assembly Guide](Assembly_Guide.md)** | A fully-illustrated, step-by-step mastercloth for putting the Alembic together safely. |
| ⚙️ **[Print Settings](Print_Settings.md)** | Essential slicer configurations, material recommendations, and orientation rules. |
| 🧭 **[Alpha State & Direction](ALPHA_&_DIRECTION.md)** | Current hardware support, active development roadmap, and how to provide feedback. |

---

> [!TIP]
> **Pneumatics and Compatible Systems**<br>
> *This toolhead uses pressurized air (similar to quiet aquarium or medical equipment pumps, rather than loud shop compressors). If you're interested in this project, check out the **[Pneuma Part Cooling](https://github.com/Alchemical-3D/Pneuma_Remote_Air)** project! It is a companion project from Alchemical-3D that provides a professional, quiet, and high-performance pneumatic air supply designed specifically to integrate seamlessly with Alembic.*

---

## 📸 Quick Glimpse

<p align="center">
  <img src="Images/full_images/alembic_face.png" width="60%" alt="Alembic Face View" style="border-radius:10px;" />
</p>

***

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. See the [LICENSE.md](LICENSE.md) file for details.

***

> ☕ **Did you find this guide helpful?** 
> 
> My projects are open-source and free for the community. If you've enjoyed my designs and want to support my work, consider [leaving me a tip on Ko-fi](https://ko-fi.com/alchemical3d)! 
>
> [![Ko-Fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/alchemical3d)
