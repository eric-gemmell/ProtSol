# ProtSolv 🧪✨
*A machine learning framework to predict protein stability in organic solvents*

![ProtSolv Logo Placeholder](./assets/protsolv_logo.png)  
*(Logo + protein structure image goes here)*

---

## 🚀 Overview
**ProtSolv** is an open-source project aimed at building and training ML models that predict how stable a protein remains when exposed to organic solvents.  
The long-term goal: provide a standardized, community-driven dataset and predictive engine for enzyme engineering and biocatalysis in non-aqueous environments.

---

## 🧩 Model Inputs
The model takes in:
- **Protein sequence** (amino acid FASTA or UniProt ID)  
- **Solvent type** (e.g. DMSO, ethanol, acetonitrile, etc.)  

---

## 📊 Dataset Requirements
For each data point, the following fields are expected:

- `solvent_type` — standardized (PubChem CID / InChIKey recommended)  
- `solvent_concentration` — % v/v or molarity  
- `residual_activity` — enzyme activity relative to 0% solvent control (%)  
- `protein_sequence` — full expressed sequence (or UniProt accession)  
- `conditions` *(optional but encouraged)*:  
  - temperature (°C or K)  
  - pH  
  - buffer type and concentration  

⚠️ **Standardization note**:  
Conditions vary across studies, so we store them as-is (with units and provenance) to preserve fidelity. A normalization strategy will evolve as the dataset grows.

---

## 🔧 Installation & Usage
Clone this repository and install requirements:
```bash
git clone https://github.com/yourusername/ProtSolv.git
cd ProtSolv
pip install -r requirements.txt

