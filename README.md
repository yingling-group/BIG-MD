# Amber_PDBtoMD: Cloud-Based Molecular Dynamics Simulations in Google Colab

Amber_PDBtoMD is a cloud-enabled, fully automated Jupyter notebook for preparing and executing all-atom molecular dynamics (MD) simulations using **AmberTools** entirely within **Google Colab** no local installation or GPU access required. Originally developed for the 2025 Biocatalyst Interactions with Gases (BIG) Symposium, this tutorial is suitable for both beginners and advanced users in biomolecular simulation and education.

---

## Features

- **Zero setup**: Runs free in your browser via Google Colab (no installation needed)
- **AmberTools-driven**: Uses SANDER CPU executable from AmberTools 24
- **Fully scripted MD workflow**:
  - PDB import and cleanup
  - Chain selection and water removal
  - Optional protonation-state correction (H++, PropKa, or Skip)
  - Force field and solvation assignment
  - Ion addition with 12-6-4 corrections
  - Short 4-stage MD simulation (minimization → heating → equilibration → production)
- **Visualization tools**: Real-time rendering via `py3Dmol`
- **Google Drive integration**: Input/output files stored automatically
- **Educational annotations**: Clear Markdown cells, diagrams, and tooltips

---

## Ideal For

- Students and educators in **computational chemistry** or **biophysics**
- Beginners to **AmberTools** and **molecular dynamics**
- Workshops and hands-on **teaching modules**
- Users without access to licensed AMBER or GPU clusters

---

## How to Use

### 1. Launch the code in Google Colab

### 2. Input a PDB ID

For example: `1V9E`, `6IM0`, etc.

### 3. Customize

- Select chains, water model, and force field
- Upload external protonation data if desired
- Adjust simulation protocol

### 4. Simulate

- Run all 4 stages:
  - Energy Minimization
  - NVT Heating (300 K)
  - NPT Equilibration (300 K, 1 bar)
  - NPT Production MD (300 K, 1 bar)

---
## Citation ##
If you use this tutorial in your teaching, workshop, or publication, please cite:

Fedai, M., Kwansa, A.L., & Yingling, Y.G. (2025). Cloud-based molecular dynamics simulations with AMBER: An interactive “collabortutorial” via Google Colab. In Proceedings of the 2025 Biocatalyst Interactions with Gases Research Symposium. North Carolina State University, Raleigh, NC, USA.