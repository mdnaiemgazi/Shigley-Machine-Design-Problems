# Shigley's Machine Design Problems - SolidWorks Simulation 

A comprehensive collection of **SolidWorks CAD models and simulations** solving selected problems from Shigley's Mechanical Engineering Design (9th Edition). This repository demonstrates practical application of machine design principles through parametric modeling, finite element analysis (FEA), and motion simulation.

[![SolidWorks](https://img.shields.io/badge/SolidWorks-2023-red.svg)](https://www.solidworks.com/)
[![GitHub](https://img.shields.io/badge/Git-LFS-blue.svg)](https://git-lfs.github.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🔧 Project Overview

### **Objective**
To solve and simulate machine design problems from *Shigley's Mechanical Engineering Design* (9th Edition) using **SolidWorks** for:
- **CAD Modeling**: Creating accurate 3D models of machine components with parametric constraints
- **Simulation**: Analyzing stress distribution, factor of safety, displacement, and motion performance
- **Technical Documentation**: Documenting the complete design process, assumptions, and results

### **Key Features**
- **SolidWorks CAD Models**: Fully parametric designs of shafts, beams, brackets, and machine elements
- **FEA Simulations**: Static stress, thermal, and factor of safety analysis with visual results
- **Motion Studies**: Dynamic simulation videos showing load conditions and deformation
- **Comparative Analysis**: Validation of simulation results against analytical calculations
- **High-Quality Visuals**: Detailed screenshots of problem setups, mesh generation, and result plots

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **SolidWorks 2023** | 3D parametric modeling, FEA simulation, motion analysis |
| **SolidWorks Simulation** | Static stress, displacement, factor of safety studies |
| **Git LFS** | Version control for large `.SLDPRT`, `.SLDASM`, and `.avi` files |
| **YouTube** | Hosting and sharing simulation walkthrough videos |
| **MS Office** | Technical report preparation and documentation |

---

## 📂 Repository Structure

```
Shigley-Machine-Design-Problems/
│
├── Assignment 1/
│   ├── beam_load_analysis.SLDPRT
│   ├── DualPlane_Loaded_Beam_Results-Displacement1.png
│   └── README.md
│
├── Assignment 2/
│   ├── Shaft_1pt5in_Torsional_Bending.SLDPRT
│   ├── Part2-Shaft_1pt5in_Torsional_Bending_Stress_Study-Image-2.png
│   └── README.md
│
├── Assignment 3/
│   ├── Brittle_Bar_Hole.SLDPRT
│   ├── Brittle_Bar_Hole_Simulation_result_comparison.png
│   └── README.md
│
├── Assignment 4/
│   ├── CraneHook_75in_x_4in.SLDPRT
│   ├── CraneHook_75in_x_4in_SectionAA_Study.png
│   └── README.md
│
├── Simulation_Videos/
│   └── [YouTube links to simulation walkthroughs]
│
└── README.md
```

---

## 📊 Featured Assignments

### **Assignment 1: Dual-Plane Loaded Beam Analysis**
[![View Simulation](https://img.shields.io/badge/Watch-Simulation-red)](https://youtu.be/1WRcmepxZgk)

**Problem:** Analysis of a beam subjected to combined uniform and point loads in dual planes.

**Simulation Results:**
- Displacement distribution under combined loading
- Stress concentration at support points
- Validation with analytical beam theory

**Sample Output:**

![Beam Load Analysis](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/blob/main/Assignment%201/beam%20load%20analysis-DualPlane_Loaded_Beam_OC_Uniform_Point_Load-Results-Displacement1.png?raw=true)

---

### **Assignment 2: Shaft Under Torsional & Bending Stress**
[![View Simulation](https://img.shields.io/badge/Watch-Simulation-red)](https://youtu.be/KlCbLn15zeI)

**Problem:** 1.5-inch diameter shaft subjected to combined torsional and bending loads.

**Simulation Results:**
- Von Mises stress distribution
- Maximum shear stress locations
- Factor of safety calculation

**Sample Output:**

![Shaft Stress Analysis](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/blob/main/Assignment%202/Part2-Shaft_1pt5in_Torsional_Bending_Stress_Study-Image-2.png?raw=true)

---

### **Assignment 3: Brittle Bar with Hole - Stress Concentration**
[![View Simulation](https://img.shields.io/badge/Watch-Simulation-red)](https://youtu.be/U0yXWie1-lY)

**Problem:** Analysis of stress concentration in a brittle material bar with a circular hole under tensile loading.

**Simulation Results:**
- Stress concentration factor (Kt) determination
- Comparison with theoretical values from Shigley's
- Failure prediction using maximum normal stress theory

**Sample Output:**

![Brittle Bar Stress Concentration](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/blob/main/Assignment%203/Brittle_Bar_Hole_Simulation_result_comparison.png?raw=true)

---

### **Assignment 4: Crane Hook Section Analysis**
[![View Simulation](https://img.shields.io/badge/Watch-Simulation-red)](https://youtu.be/GkhKZPQMsn4)

**Problem:** Curved beam analysis of a crane hook with 0.75" × 4" cross-section.

**Simulation Results:**
- Stress distribution across curved section
- Neutral axis shift calculation
- Comparison with Winkler-Bach curved beam theory

**Sample Output:**

![Crane Hook Analysis](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/blob/main/Assignment%204/CraneHook_75in_x_4in_SectionAA_Study.png?raw=true)

---

### **Bonus: Additional Simulation**
[![View Simulation](https://img.shields.io/badge/Watch-Simulation-red)](https://youtu.be/stoksNx1EBA)

**Problem:** Supplementary machine element analysis demonstrating advanced simulation capabilities.

---

## 🎯 Problem Statements & Objectives

| Assignment | Shigley's Reference | Objective |
|------------|-------------------|-----------|
| **Assignment 1** | Beam Deflection Problems | Validate FEA displacement results against analytical beam equations |
| **Assignment 2** | Shaft Design Chapter | Analyze combined torsional and bending stresses in rotating shafts |
| **Assignment 3** | Stress Concentration | Determine Kt for geometric discontinuities in brittle materials |
| **Assignment 4** | Curved Beams | Compare FEA results with Winkler-Bach curved beam theory |

---

## 📈 Key Outcomes

Each assignment delivers:
- ✅ **Parametric CAD models** ready for design iteration
- ✅ **FEA validation** comparing simulation with analytical solutions
- ✅ **Factor of safety** determination for design feasibility
- ✅ **Visual documentation** of stress, displacement, and failure modes
- ✅ **Step-by-step methodology** following Shigley's design approach

---

## 🚀 Getting Started

### Prerequisites
- **SolidWorks 2020 or later** (for opening `.SLDPRT` and `.SLDASM` files)
- **Git LFS** (for cloning large binary files)
```bash
git lfs install
```

### Clone Repository
```bash
git clone https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems.git
cd Shigley-Machine-Design-Problems
```

### View Files
1. **CAD Models**: Open `.SLDPRT` files in SolidWorks
2. **Simulations**: Watch `.avi` files or YouTube links
3. **Results**: View PNG images for quick reference
4. **Documentation**: Read individual `README.md` in each assignment folder

---

## 📚 Methodology

1. **Problem Definition**: Identify Shigley's problem statement and design requirements
2. **Analytical Solution**: Calculate theoretical values using textbook equations
3. **CAD Modeling**: Create parametric 3D models in SolidWorks
4. **Simulation Setup**: Apply materials, fixtures, and loads matching problem conditions
5. **FEA Analysis**: Run static studies with appropriate mesh refinement
6. **Validation**: Compare FEA results with analytical calculations
7. **Documentation**: Compile findings with visual evidence

---

## 📥 Large File Notice

This repository uses **Git LFS** for binary files including:
- SolidWorks part files (`.SLDPRT`)
- Assembly files (`.SLDASM`)
- Simulation videos (`.avi`)

Ensure Git LFS is installed before cloning to properly download all files.

---

## 👨‍🔬 Author Information

**MD Naiem Gazi**  
*Mechanical Engineering Graduate*

- **Email**: [mdnaiemgazi@outlook.com](mailto:mdnaiemgazi@outlook.com)
- **Portfolio**: [https://mdnaiemgazi.github.io/portfolio/](https://mdnaiemgazi.github.io/portfolio/)
- **GitHub**: [@mdnaiemgazi](https://github.com/mdnaiemgazi)
- **LinkedIn**: [MD Naiem Gazi](https://www.linkedin.com/in/md-naiem-gazi-7186361b2/)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📌 Quick Access

| Assignment | YouTube Simulation | GitHub Folder |
|------------|-------------------|---------------|
| **Assignment 1** | [Watch](https://youtu.be/1WRcmepxZgk) | [View Folder](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/tree/main/Assignment%201) |
| **Assignment 2** | [Watch](https://youtu.be/KlCbLn15zeI) | [View Folder](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/tree/main/Assignment%202) |
| **Assignment 3** | [Watch](https://youtu.be/U0yXWie1-lY) | [View Folder](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/tree/main/Assignment%203) |
| **Assignment 4** | [Watch](https://youtu.be/GkhKZPQMsn4) | [View Folder](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems/tree/main/Assignment%204) |
| **Bonus** | [Watch](https://youtu.be/stoksNx1EBA) | [View Main](https://github.com/mdnaiemgazi/Shigley-Machine-Design-Problems) |

---

*This repository demonstrates proficiency in SolidWorks CAD modeling, FEA simulation, and application of machine design principles from Shigley's textbook.*
