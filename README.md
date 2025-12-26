# AChE–Donepezil Docking Contact Analysis

---

## Overview
This project investigates the amino acid residues of acetylcholinesterase (AChE) that are most frequently involved in interactions with Donepezil. Residue–ligand contacts within a 4 Å distance were extracted from multiple docking poses and analyzed to identify residues that consistently contribute to ligand binding.

---

## Workflow
Protein structure (1EVE)  
→ Donepezil docking with multiple poses  
→ Contact extraction in PyMOL (4 Å cutoff)  
→ Contact gathering across poses  
→ Frequency analysis in Python  
→ Visualization in Jupyter Notebook  

---

## Aim
The aim of this study is to move beyond single-pose docking analysis by incorporating multiple docking poses and evaluating contact frequency as an indicator of interaction stability. Residues that repeatedly appear in contact with Donepezil across different poses are considered more likely to play a significant role in binding.

---

## Materials and Methods

### Structural Data
The protein structure used in this study is acetylcholinesterase (PDB ID: 1EVE). Donepezil was used as the ligand. Docking output containing multiple ligand poses served as the input for contact analysis.

---

### Contact Definition
A contact was defined when any atom of a residue was located within 4 Å of any atom of the ligand. Contacts were identified separately for each docking pose.

---


### Tools and Software
PyMOL was used for molecular visualization and residue selection. Contact data were exported as CSV files and analyzed using Python with pandas. Data visualization was performed in Jupyter Notebook using matplotlib.

---


## Analysis
Contacts from all docking poses were gathered and grouped by residue name, residue number, and chain identifier. Residues were ranked based on their frequency of occurrence across all poses. Higher contact frequency was interpreted as stronger or more stable involvement in ligand binding.

---

## Results and Interpretation
Several residues appear consistently across multiple docking poses, suggesting stable participation in Donepezil binding. Aromatic residues show particularly high contact frequencies, which is consistent with known features of the acetylcholinesterase active site.

---

<img width="790" height="490" alt="top15" src="https://github.com/user-attachments/assets/32603244-b8a8-4029-bf7b-faba6d6941c7" />

---

## for jupyter notebook: https://github.com/kubrayill/ache-donepezil-docking/blob/main/analysis/analysis.ipynb

---
