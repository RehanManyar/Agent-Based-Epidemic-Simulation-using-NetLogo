# 🦠 EPIDEMIC SIMULATOR X
### Agent-Based Epidemic Simulation Using NetLogo

An interactive scientific simulation that demonstrates how infectious diseases spread through a moving population, and how vaccination, recovery, and social distancing influence epidemic dynamics.

<p align="center">
  <b>Built with NetLogo | Agent-Based Modeling | Scientific Visualization</b>
</p>

---

## 📌 Overview

**EPIDEMIC SIMULATOR X** is an agent-based epidemic simulation developed using NetLogo.

The model represents individuals as autonomous agents moving inside a simulated environment. Each agent has a health state, and interactions between nearby agents determine how an infection can spread through the population.

The simulation provides a visual and statistical representation of epidemic progression, from initial infection to outbreak development and recovery.

## ✨ Key Features

- **Agent-Based Population:** Represents individuals as independently moving agents.
- **Disease Transmission:** Simulates infection through proximity-based interactions and configurable transmission probability.
- **Vaccination System:** Represents vaccinated individuals separately.
- **Recovery Mechanism:** Models the transition from infected to recovered states.
- **Social Distancing:** Includes a configurable social-distancing control.
- **Movement Engine:** Controls agent movement and population interaction.
- **Scientific Visualization:** Displays population states using colour-coded agents.
- **Live Statistics:** Tracks healthy, infected, vaccinated and recovered populations.
- **Epidemic Analytics:** Visualizes population changes through an epidemic curve.
- **Simulation Controls:** Initialize, start and stop the simulation interactively.

## 🧬 Population Health States

| Colour | Health State | Description |
|---|---|---|
| 🟢 Green | Healthy / Susceptible | Individuals who can become infected |
| 🔴 Red | Infected | Individuals currently carrying the infection |
| 🔵 Cyan | Recovered | Individuals who have recovered |
| 🟣 Purple | Vaccinated | Individuals belonging to the vaccinated group |

## ⚙️ Simulation Parameters

| Parameter | Captured Value | Function |
|---|---:|---|
| Population Size | 605 | Total simulated population |
| Infection Probability | 38 | Transmission probability setting |
| Infection Radius | 1.5 | Distance for possible transmission |
| Recovery Time | 43 | Time required for recovery |
| Vaccination Rate | 15 | Vaccination setting |
| Movement Speed | 0.4–0.5 | Agent movement speed |
| Social Distancing | ON/OFF | Configurable distancing control |

## 📊 Simulation Observations

The following results were recorded from three stages of a simulation run.

| Simulation Stage | Healthy | Infected | Recovered | Vaccinated |
|---|---:|---:|---:|---:|
| Initial Stage | 502 | 1 | 0 | 102 |
| Active Outbreak | 319 | 153 | 31 | 102 |
| Post-Outbreak | 10 | 0 | 493 | 102 |

**Key Observation:** In the captured run, active infections increased from 1 to a peak of 178 simultaneous infections. Eventually, active infections reached zero, with 493 recovered individuals.

These are observations from one simulation run, not predictions of real-world epidemic behaviour.

## 🖥️ Project Interface

The simulation interface consists of three main areas:

1. **Control Panel:** Simulation buttons, parameter sliders and social-distancing switch.
2. **Statistics & Epidemic Curve:** Live population counters and graphical outbreak progression.
3. **Simulation Environment:** Animated agents representing the population and their health states.

## 🛠️ Technology Stack

- **Simulation Environment:** NetLogo
- **Modeling Approach:** Agent-Based Modeling (ABM)
- **Visualization:** NetLogo Interface and Plots
- **Model Source:** NetLogo model file

## 🚀 Getting Started

1. Download or clone this repository.
2. Install a compatible NetLogo Desktop version.
3. Open the `AI.nlogox` model file using a compatible NetLogo environment.
4. Initialize the simulation.
5. Adjust the available parameters.
6. Start the simulation and observe the population dynamics.

**Compatibility Note:** The uploaded model metadata identifies NetLogo 7.0.4, while its source comments mention NetLogo Desktop 6.4.0. Verify compatibility with your installed version before running.

## 📂 Repository Structure

```text
Agent-Based-Epidemic-Simulation-using-NetLogo/
│
├── AI.nlogox
├── Epidemic Simulator X Academic Report.pdf
└── README.md
```

## 📄 Project Documentation

The academic report includes:

- Project objective and overview
- Model entities and health states
- Simulation rules and working mechanism
- Parameters and controls
- Experimental observations
- Results and analysis
- Original simulation screenshots
- AI tools disclosure

📘 [View Academic Project Report](./Epidemic%20Simulator%20X%20Academic%20Report.pdf)

## 🎓 Academic Context

Developed as an individual Open-Ended Assignment for **Artificial Intelligence-I**, Academic Year 2026–27.

**Student:** Rehan Aarif Manyar  
**Programme:** B.Tech – Computer Science and Engineering (Data Science)

## 🤖 AI Assistance Disclosure

ChatGPT (OpenAI) was used for assistance with simulation planning, code suggestions and explanations, and technical report preparation.

The model was executed to generate the simulation observations and screenshots included in the project documentation.

## ⚠️ Disclaimer

This project is an educational simulation intended to demonstrate agent-based modeling and basic epidemic dynamics. It is not a medical tool, epidemiological forecasting system, or substitute for scientific public-health research.

## 👨‍💻 Author

**Rehan Aarif Manyar**

GitHub: [@RehanManyar](https://github.com/RehanManyar)

---

<p align="center">
  <b>EPIDEMIC SIMULATOR X</b><br/>
  Exploring Disease Dynamics Through Agent-Based Modeling.
</p>
