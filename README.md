# Cyclodextrin–Drug Inclusion Complexes

**An Integrated Meta-Analysis and Molecular Modeling Study**

## 📌 Overview

Cyclodextrin (CD) inclusion complexes are widely used to enhance drug solubility and bioavailability. This project integrates **meta-analysis** with **molecular modeling** to systematically evaluate the pharmacokinetic performance and molecular stability of various cyclodextrin–drug systems.

The study combines:

* Quantitative meta-analysis of in vivo pharmacokinetic data
* Molecular docking
* Molecular dynamics (MD) simulations
* Free energy calculations

to provide both **statistical** and **mechanistic** insight into cyclodextrin selection for formulation development.

---

## 🎯 Objectives

* Quantify the impact of cyclodextrin inclusion on drug exposure using **Cmax** and **AUC** effect sizes
* Identify the most effective cyclodextrin derivatives for improving bioavailability
* Investigate host–guest stability and binding mechanisms at the molecular level
* Link molecular interactions to observed pharmacokinetic outcomes

---

## 📊 Meta-Analysis

* **Number of studies:** 11
* **Outcomes analyzed:**

  * Maximum concentration (Cmax)
  * Area under the curve (AUC)
* **Key findings:**

  * Significant overall improvement in drug exposure
  * Substantial heterogeneity across studies
  * **SBE-β-cyclodextrin (SBE-β-CD)** showed the strongest enhancement of bioavailability
  * **γ-cyclodextrin (γ-CD)** was consistently the least effective

---

## 🧪 Molecular Modeling

### Methods

* Molecular Docking
* Molecular Dynamics (MD) simulations
* Binding free energy calculations

### Systems Studied

Selected ligands based on solubility (logS):

* Atorvastatin (ATV)
* β-Caryophyllene
* Koumine
* Compound K

### Key Molecular Insights

* Compound K/β-cyclodextrin exhibited higher binding affinity than ATV/HP-β-CD
* All ligands showed stronger affinity for **SBE-β-CD** compared to **γ-CD**
* Replicate MD simulations (Compound K and koumine) confirmed greater stability with SBE-β-CD
* Enhanced stability attributed to:

  * Extended hydrophobic cavity of SBE-β-CD
  * Reduced electrostatic repulsion
  * Favorable molecular shape complementarity

---

## 🔬 Main Conclusions

* **SBE-β-CD** is the most effective cyclodextrin for improving drug bioavailability
* Molecular shape and hydrophobicity play a critical role in complex stability
* Computational results align well with pharmacokinetic effect sizes from meta-analysis
* Provides a mechanistic framework for rational cyclodextrin selection in drug formulation

---

## ⚠️ Limitations

* Findings are based on computational modeling and preclinical data
* Further **clinical validation** is required to confirm translational relevance

---

## 🧠 Significance

This integrated framework bridges **statistical evidence** and **molecular mechanisms**, offering a rational, data-driven approach to cyclodextrin selection in pharmaceutical development.

---

## 📁 Repository Contents

```
├── meta_analysis/
│   ├── data/
│   ├── scripts/
│   └── results/
├── docking/
├── molecular_dynamics/
├── free_energy/
└── README.md
```



