# Wood-Chair-Analysis
# Static Structural Analysis of a Wood Chair 


## 📌 Project Overview
This project uses **Ansys Mechanical** to perform a Finite Element Analysis (FEA) on a critical component of a wood chair (`Chair|Cut-Extrude6`). The primary objective was to validate the structural integrity under design loads, focusing on the material limitations of wood. The project calculates the **Factor of Safety (FoS)** to ensure the component can reliably withstand typical operational stresses without yielding.

## ⚙️ Simulation Setup and Methodology

### 1. Geometry and Mesh
* **Component Analyzed:** A specific structural part of a chair (`Chair|Cut-Extrude6`).
* **Meshing:** The geometry was discretized using an optimized mesh, which included **Body Sizing** to accurately capture stress flow and concentrations, particularly at joints and load-bearing areas.

### 2. Material Properties: Wood
The component is modeled using **Wood** properties, acknowledging its inherent anisotropic nature (though modeled here with isotropic elasticity, as is common for preliminary FEA).
* **Density:** 946 kg/m³
* **Stress Limit Type:** Tensile Yield Per Material
* **Key Property:** Tensile Yield Strength (used as the safety limit).

### 3. Boundary Conditions & Loads
* **Loads:** Static loads (forces or pressure) simulating the weight and forces exerted by a person sitting on the chair.
* **Constraints:** Defined fixed supports or appropriate displacement constraints to anchor the model.

## 📊 Results & Structural Validation

### 🔍 Key Findings
The simulation successfully converged, demonstrating the component's performance relative to the material limits.

1.  **Safety Factor (FoS):**
    * **Minimum Safety Factor:** **1.6573**
    * The safety factor is above the general engineering threshold of 1.0, but closer to it than the previous steel project (FoS 9.8). This indicates the design is structurally safe but utilizes the material more efficiently, or that the design is closer to its failure limit under the design load.

2.  **Governing Stress:**
    * The safety factor was calculated based on the maximum **Equivalent (von Mises) Stress** criterion against the tensile yield strength of wood.
    * The minimum safety factor occurred on the part named `Chair|Cut-Extrude6`.


## 🚀 Repository Contents
* `Project.wbpj`: The Ansys Workbench project file.
* `Wood chair.pdf`: The detailed simulation report.

---
## 👨‍💻 Author
**Yazan Alzyuod**
* **Mechanical Engineer**
* 📧 [yqlasem@gmail.com](mailto:yqlasem@gmail.com)
* 🔗 [LinkedIn Profile](https://www.linkedin.com/in/yazan-alzyuod)
* 💻 [GitHub Profile](https://github.com/Yazan-Alzyuod)
* 📞 00962775327776
