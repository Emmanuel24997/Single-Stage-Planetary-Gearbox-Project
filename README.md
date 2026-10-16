# Single-Stage Planetary Gearbox Design Project

A custom single-stage planetary gearbox assembly modeled, simulated, and animated in SOLIDWORKS.

## 📸 Visual Showcase

![Gearbox Assembly](Renders/isometric-view.png)

## 📊 Technical Specifications

| Parameter | Specification |
| :--- | :--- |
| **Gearbox Type** | Single-Stage Epicyclic / Planetary Gear Train |
| **Arrangement** | Sun Gear (Input), 3x Planet Gears, Planet Carrier, Fixed Ring Gear |
| **Material Selection** | Cold Rolled Steel & Gray Carbon Steel (Planet Gears) |
| **Simulation** | Motion Study (Rotary Motor & Kinematic Validation) |

## ⚙️ Design & Manufacturing Highlights

* **Part modelling from Scratch:** modelled all the parts from scratch using sketches and features like extrude, extrude cut, etc. All the gear teeth were custom made also.
* **Gear Ratios:** The sun gear and the three planet gears all had 15 teeth.Crafted the ring gear with 45 teeth to guide the planet gears. 
* **Material Application:** Applied cold rolled steel and gray carbon steel to the planet gears and structural components for realistic physical properties and visual contrast.
* **Motion Study & Animation:** Simulated a rotary motor drive on the sun gear to show it's performance in real time and generated exploded view animations.
* **Assembly Validation:** All components of the assembly were perfectly mated and are fully functional as they were rotating as they should. Although I wasn't able to prevent the teeth of the gears from phasing through each other. I am aware the structure of the gear teeth is responsible for this and I intend correcting it later.

## 📁 Repository Directory Structure

```text
single-stage-planetary-gearbox/
├── CAD/
│   ├── Gearbox_Assembly.step
│   └── ...
├── Renders/
│   └── isometric-view.png
├── Animations/
│   └── motion-study.mp4
└── Docs/
    └── specs.txt
