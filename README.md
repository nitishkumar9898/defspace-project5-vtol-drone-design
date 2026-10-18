# Project 5 — VTOL Drone Design Portal

**Def Space Summer Internship 2026 | Bharat Space Education Research Centre**

## Student
- **Name:** Nitish Kumar Kannaujiya
- **Roll No.:** 24BECCS33
- **Course:** B.Tech CSE (Cybersecurity), 5th Semester
- **University:** Central University of Jammu

## About This Project
Conceptual design portal for a **quadrotor VTOL UAV** intended for aerial survey at low altitude (≤50m AGL). Covers frame selection, propulsion sizing, electronics stack, weight budget, and performance estimation with an interactive propulsion calculator.

## Key Design Specs
| Parameter | Value |
|-----------|-------|
| Frame | X-frame quadrotor, 450mm diagonal |
| Motor | 2212 / 920KV BLDC × 4 |
| Propeller | 10×4.5 inch × 4 |
| Battery | 3S 5200mAh 35C LiPo |
| Max AUW | 1200 g |
| Payload | 200 g (camera/sensor) |
| Thrust-to-Weight | 2.67 |
| Hover Throttle | ~45% |
| Flight Time (hover) | ~18 minutes |

## Features
- 🗂️ 6-tab interactive portal
- 🚁 SVG X-frame quadrotor top-view diagram (CCW/CW motor labels)
- ⚙️ Full electronics stack specification
- 🧮 Interactive propulsion calculator — live sliders for AUW, motors, efficiency, battery
- 📊 Thrust vs Throttle chart (Chart.js)
- 📊 Flight Time vs Payload chart
- 📊 Thrust vs Battery Cell Count chart
- 🔩 Weight budget breakdown
- 📋 Full design results table vs targets

## How to Run
Open `index.html` directly in any browser — no server or build step required.

## Live Demo
Deployed via GitHub Pages: https://nitishkumar9898.github.io/defspace-project5-vtol-drone-design/
