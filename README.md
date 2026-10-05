# Hi, I'm Mingze Wang 👋

I am an aerospace engineering student at **Beihang University**, with interests in **laser diagnostics, scientific instrumentation, experimental research, embedded systems, and scientific computing**.

My work lies at the intersection of **physics, computation, electronics, and engineering systems**. I enjoy taking a problem from first-principles modelling and numerical simulation all the way to hardware implementation, experiments, measurement, and data analysis.

I am currently preparing for doctoral research in **laser-based measurement and scientific instrumentation for aerospace applications**.

---

## 🔬 Research Interests

My current and long-term interests include:

- **Laser diagnostics and optical measurement**
- **Scientific instrumentation**
- **Experimental fluid mechanics**
- **Optics and laser systems**
- **Aerospace propulsion and energy systems**
- **Scientific computing and numerical simulation**
- **Embedded control and sensing systems**
- **Research software and scientific data infrastructure**
- **Reproducible computational research**

I am particularly interested in research that connects:

> **Model → Simulation → Hardware → Experiment → Measurement → Physical Understanding**

---

## 🚀 Current Focus

I am currently strengthening my background in:

- Physical optics
- Laser physics
- Nonlinear optics
- Optical measurement techniques
- Laser-based flow diagnostics
- Experimental instrumentation
- Research software infrastructure
- Reproducible scientific workflows

My long-term goal is to develop reliable and high-performance **measurement systems, research instruments, and computational infrastructure** for aerospace and fluid-mechanics research.

---

# 🧪 Selected Research & Engineering Projects

## 🗂️ Research Project Lifecycle Repository

**In development**

A long-term research infrastructure project designed to manage scientific projects throughout their complete lifecycle — from initial ideas and source code to simulation models, experimental data, hardware designs, results, documentation, and final research outputs.

The project is motivated by a simple problem:

> Research artifacts are often scattered across folders, computers, simulation environments, Git repositories, documents, and temporary outputs, making long-term traceability and reproducibility difficult.

The system is designed to organize and connect major research artifacts such as:

- Source code
- Numerical models
- Simulation configurations
- Simulation results
- Experimental data
- PCB and hardware designs
- Firmware
- Technical documentation
- Research reports
- Figures and processed datasets
- Validation records
- Final research outputs

A central concept is the construction of a **Computational Experiment Traceability Chain**:

```text
Research Question
       ↓
Method / Model
       ↓
Source Code
       ↓
Simulation / Experiment Definition
       ↓
Input Parameters
       ↓
Execution
       ↓
Raw Results
       ↓
Processed Data
       ↓
Figures / Analysis
       ↓
Report / Paper
```

The goal is to make every important research result traceable back to the code, model, parameters, data, and assumptions that produced it.

The repository architecture considers several layers:

```text
git
 └── Source code and research software

sim
 └── Simulation models and experiment definitions

data
 └── Simulation results, experimental data,
     hardware designs, and research artifacts

ctrl
 └── Future automation and control interfaces
```

The project is also exploring a **self-hosted research software registry**, intended to provide long-term management of research software, project documentation, and reusable computational tools.

Long-term objectives include:

- Full research-artifact lifecycle management
- Reproducible computational experiments
- Version-controlled scientific workflows
- Automated project indexing
- Research software registry
- Data provenance tracking
- Code–model–data association
- Hardware–software traceability
- Project-level knowledge organization
- Support for future AI-assisted research workflows

This project is intended to evolve continuously throughout my undergraduate, doctoral, and future research work.

---

## 🧠 ResearchLLM — Personal Research AI Infrastructure

**In development**

A private AI-assisted research knowledge infrastructure designed for long-term scientific work.

The system is intended to manage and retrieve research knowledge including:

- Papers
- Research notes
- Experimental records
- Project documentation
- Source code
- Simulation results
- Technical manuals
- Research decisions
- Development logs

The architecture follows the principle that **research knowledge should remain independent of any single AI model**.

```text
Research Assets
     ↓
Document Processing
     ↓
Embedding
     ↓
Vector Database
     ↓
Retrieval-Augmented Generation
     ↓
Replaceable Local / Cloud LLM
```

The infrastructure currently explores:

- AnythingLLM
- Ollama
- Local language models
- Embedding models
- Vector databases
- Retrieval-Augmented Generation (RAG)
- Automatic document ingestion
- GitHub integration
- Notion integration
- Research knowledge synchronization

The long-term goal is to build a persistent **Personal Research AI Infrastructure** in which models can be replaced while research knowledge, project history, and scientific data remain durable assets.

Potential future development includes deployment for research groups as private research knowledge infrastructure.

---

## ⚡ Hybrid Energy System for a Long-Endurance UAV

Design and simulation of a **solar–battery–hydrogen fuel-cell hybrid energy system** for a long-endurance fixed-wing UAV.

The project investigates the coupled relationship between aircraft mass, propulsion power demand, energy storage, system architecture, and mission endurance.

Main topics include:

- Aircraft aerodynamic and power-demand modelling
- Mass–power–energy iterative closure
- Solar photovoltaic modelling
- Lithium-ion battery modelling
- Hydrogen fuel-cell modelling
- Energy Management System (EMS)
- MATLAB / Simulink / Stateflow
- Parameter sensitivity analysis
- Feasibility-boundary analysis
- Single-, dual-, and triple-energy architecture comparison
- Motor-power feasibility analysis
- EMS hardware and PCB exploration

🔗 [Electric Propulsion Class Design](https://github.com/huaqing0617-wang/electric-propulsion-class-design)

The project was developed through multiple generations of models, including corrections to aerodynamic assumptions, mission-level simulation, mass closure, EMS optimisation, hardware constraints, and final integrated analysis.

---

## 🤖 Wall Patrol One

An autonomous wall-inspection robotic platform integrating embedded control, sensing, communication, power electronics, and mechanical design.

The system currently combines:

- STM32G474
- Raspberry Pi 5
- Custom control PCB
- Motor drivers
- CAN communication
- IMU sensing
- OLED human-machine interface
- Remote Linux development
- Embedded firmware
- Magnetic adhesion
- Mobile-platform control

The project covers the complete engineering process:

```text
System Requirements
       ↓
Architecture Design
       ↓
Schematic
       ↓
PCB
       ↓
Firmware
       ↓
Embedded Linux
       ↓
Communication
       ↓
Motor Control
       ↓
System Integration
       ↓
Experimental Validation
```

The project is being developed as a complete hardware–software robotic system rather than an isolated embedded prototype.

---

## 🏊 Swimming Biomechanics with SWUM

Numerical investigation of swimming biomechanics using **SWUM**, including freestyle and breaststroke studies.

Research topics include:

- Hydrodynamic force analysis
- Stroke-cycle time histories
- Multi-cycle convergence
- Periodic stability
- Single-factor sensitivity studies
- Two-factor interaction analysis
- Multi-objective evaluation
- Pareto analysis
- Propulsive-force characteristics
- Biomechanical interpretation

The work emphasizes not only peak values or isolated metrics, but also temporal evolution, cycle-integrated quantities, fluctuations, phase relationships, and multi-objective performance.

---

# 💻 Programming & Scientific Computing

## Languages

- Python
- MATLAB
- C / C++
- Shell

## Numerical & Engineering Tools

- MATLAB
- Simulink
- Stateflow
- ANSYS Workbench
- ANSYS Fluent
- OpenFOAM
- SWUM

## Embedded Systems

- STM32
- Raspberry Pi
- UART
- I²C
- SPI
- CAN
- PWM
- ADC
- Motor control
- Sensor integration

## Electronics & Hardware

- PCB design
- Schematic design
- Power electronics
- MOSFET switching
- Power distribution
- Sensor interfaces
- Embedded control boards
- Hardware debugging

## Research & Development

- Git
- GitHub
- VS Code
- Linux
- macOS
- SSH
- Raspberry Pi OS
- Research data organization
- Reproducible computational workflows

---

# 🧠 Research & Engineering Philosophy

I prefer research and engineering workflows that are:

**Physics-based**  
Models should remain consistent with the underlying physical mechanisms.

**Reproducible**  
Results should be traceable to source code, input parameters, models, and data.

**Auditable**  
Assumptions, parameters, intermediate decisions, and model evolution should be documented.

**Version-controlled**  
Important changes in code, models, hardware, and documentation should remain recoverable.

**Experiment-oriented**  
Simulation should ultimately contribute to measurement, validation, experimental design, or physical understanding.

**System-level**  
Software, electronics, mechanics, modelling, data, and experiments should be treated as components of one engineering system.

**Lifecycle-aware**  
A research result should not exist independently of the code, data, configuration, assumptions, and experimental context that produced it.

---

# 📚 Currently Learning

I am currently studying the theoretical foundations required for future work in laser-based measurement and scientific instrumentation, including:

- Physical optics
- Interference and diffraction
- Fourier optics
- Laser fundamentals
- Nonlinear optics
- Optical measurement
- Laser diagnostics
- Experimental fluid mechanics

I am also continuously developing skills in:

- Scientific software engineering
- Research data management
- Reproducible computing
- Embedded instrumentation
- AI-assisted scientific workflows

---

# 🎯 Long-Term Direction

My long-term research interests lie in developing advanced measurement technologies and scientific instruments for aerospace and fluid-mechanics research.

I am particularly interested in systems that combine:

```text
            Optics
              +
            Lasers
              +
       Fluid Mechanics
              +
         Electronics
              +
    Scientific Computing
              +
       Instrumentation
              +
 Research Data Infrastructure
              ↓
 Advanced Experimental & Measurement Systems
```

I want to develop not only individual algorithms or devices, but complete research systems in which:

```text
Theory
  ↓
Model
  ↓
Simulation
  ↓
Hardware
  ↓
Experiment
  ↓
Measurement
  ↓
Data
  ↓
Analysis
  ↓
Scientific Knowledge
```

remains connected and traceable.

---

# 📌 Why I Use GitHub

I use GitHub not only as a code-hosting platform, but as part of a long-term scientific research infrastructure.

My repositories may contain:

- Source code
- Numerical models
- Simulation workflows
- Experimental tools
- Embedded firmware
- PCB and hardware designs
- Research documentation
- Processed datasets
- Validation records
- Reproducible analyses
- Research software
- Technical studies

Where possible, I aim to make projects:

**Reproducible · Traceable · Auditable · Maintainable · Understandable**

rather than preserving only the final result.

---

# 📫 About Me

**Mingze Wang**

Beihang University  
Aerospace Engineering

Research interests:

**Laser Diagnostics · Scientific Instrumentation · Experimental Fluid Mechanics · Embedded Systems · Scientific Computing · Research Infrastructure**

---

> **Build. Simulate. Measure. Understand.**
