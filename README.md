# Multi-Mission Weapon System ROI Analysis

## Overview

This project presents a structured, data-driven framework for evaluating the return on investment (ROI) and mission alignment of both traditional and non-traditional military weapon systems. It compares platforms (e.g., aircraft, artillery) and munitions (e.g., guided rounds, loitering drones) based on normalized performance metrics and mission-specific scoring profiles.

The objective is to demonstrate that high ROI and operational value can often be achieved with lower-cost, modular, or autonomous systems—depending on mission type. This notebook enables quantitative comparison between systems and helps decision-makers or analysts prioritize modernization strategies with context-specific insight.

---

## Key Features

- 📊 **Multi-dimensional Data Modeling**  
  Includes cost, range, payload, reusability, and mission fit.

- 🧮 **ROI Scoring Engine**  
  Normalizes metrics and applies mission-specific weighting to compute performance scores.

- 🧠 **Mission Profile Filtering**  
  Only compares systems that are relevant to a given mission (e.g., excludes torpedoes from Close Air Support).

- 📈 **Interactive Visualizations**  
  Uses Plotly to generate dynamic bar charts per mission type to visualize top-performing systems.

- ⚙️ **Fully Reusable and Extensible**  
  Add new systems, missions, or scoring logic with minimal code changes.

---

## Missions Evaluated

- **Fires Support** (formerly Close Air Support)
- **ISR** (Intelligence, Surveillance, Reconnaissance)
- **Anti-Ship / ASW** (Anti-Submarine Warfare)
- **Air Defense** (C-UAS and intercept systems)

Each mission includes its own weight profile emphasizing metrics that matter most (e.g., payload for Fires Support, endurance for ISR).

---

## Technologies Used

- `pandas` – for data modeling and transformation  
- `scikit-learn` – for metric normalization  
- `plotly.express` – for interactive plotting  
- `Jupyter Notebook` – for interactive exploration and documentation

---

## How to Use

1. Clone this repository.
2. Open the notebook: `Hammerschmidt_Data720 Final Project.ipynb` in Jupyter.
3. Run all cells from top to bottom.
4. Explore each mission’s scoring output and plots.

You can add new systems, tweak mission weightings, or re-define relevance tags to adapt the analysis to different operational questions.

---

## Applications

This framework is suitable for:
- Defense acquisition support
- Digital force design exercises
- Wargaming modernization tradeoffs
- Policy analysis for emerging technologies

---

## Author

This project was created by Dave Hammerschmidt as part of the **DATA 720 - Applied Data Science** course at the University of North Carolina at Chapel Hill.

For follow-up or collaboration, please reach out via GitHub or LinkedIn.

---
