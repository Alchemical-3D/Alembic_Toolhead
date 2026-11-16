# 🧭 Alembic Toolhead: Alpha State & Development Direction

Alembic is currently in an active **Alpha State** of development. This document outlines the current state of the project, verified hardware compatibility, and staged upgrades as we progress toward a Beta release.

> [!WARNING]
> **Active Development Notice**  
> While we have working models that perform exceptionally well in testing, this toolhead is still evolving. Builders taking on the Alpha release should be prepared for iterative refinements to geometry, hardware requirements, or the [Bill of Materials (BOM)](BOM.md) as the project matures.

---

## 🏗️ Current State (Alpha)

The Alembic Toolhead has proven the viability of replacing traditional toolhead blowers with high-speed, remote compressed air for precision part cooling—penetrating the thermal boundary layer while keeping moving carriage mass remarkably low.

### Current Hardware Compatibility

- **Extruders:** Currently designed around the **[A3DP FXD](https://kb-3d.com/store/extruders-hotends/9466-a3dp-fxd-fixed-gear-extruder-v11-1776099901694.html?affp=6182)** fixed-gear extruder.
- **Hotends:** Direct support built in for both the **Takoto** (`Fan_Baffle_Takoto.stl`) and **Dragon** (`Fan_Baffle_Dragon.stl`) hotends, including dedicated BDsensor retainers and shims for each.
- **Gantry Mount:** Native fitment for the **[A3DP Gantry Assembly](https://github.com/Alchemical-3D/A3DP_Gantry_Assembly)** milled aluminum X-carriage.

We expect hardware compatibility to widen significantly throughout Alpha and Beta testing.

---

## 🗺️ Roadmap & Intended Changes

As we prepare the transition from Alpha to Beta, several modular expansions and aerodynamic refinements are being staged:

> [!NOTE]
> **📝 Highlighted Concepts & Planned Features**
> 
> *The following modular expansions and hardware additions are currently under active investigation and development:*
> 
> - **Expanded Extruder Compatibility:** Designing adapters and core mounts to support a wider array of popular extruders beyond the A3DP FXD.
> - **Expanded Hotend Compatibility:** Bringing support for additional high-flow and standard hotends beyond the Takoto and Dragon.
> - **Airflow Optimization:** Continuous iterations and empirical tuning of the internal pneumatic manifold and aluminum tube geometry to maximize cooling efficiency.
> - **Weight Reduction & Structural Tuning:** Refining the carriage and manifold geometry to shave off additional grams without sacrificing rigidity.

*(Note: Features and concepts listed here are subject to change based on testing constraints, empirical results, and community feedback.)*

---

## 📣 We Need Your Feedback!

Because Alembic relies on a focused pneumatic cooling architecture, **community feedback from real builds is exceptionally valuable** for optimizing performance across different filaments, speeds, and nozzle geometries.

If you are an Alpha builder or are planning a build, we want to hear from you! Please share your prints, airflow observations, and suggestions for improvements.

### Join the Conversation

All development discussion, testing feedback, and hardware requests take place in our community Discord server:

👉 **Join the discussion in the `#alembic-toolhead` channel on the [Alchemical-3D Discord](https://discord.gg/aE49DW2xXe)!**

***
*Documentation prepared with AI editorial assistance • Engineered & maintained by Alchemical-3D.*
