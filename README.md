# Analysis of AChE–Donepezil Interactions Using PyMOL and Python

##  Project Overview
This project investigates the interactions between **acetylcholinesterase (AChE)** and the Alzheimer’s drug **Donepezil**.  
Using **PyMOL**, amino acid residues located within **4 Å** of Donepezil in the AChE binding pocket were identified.  
The resulting contact data were then analyzed and visualized in **Python (Jupyter Notebook)**.

The goal of this project is to identify amino acid residues located within 4 Å of Donepezil and to rank them based on the number of atomic contacts observed in a single docked structure.

Note: Contact counts were obtained from a single docked structure and represent atomic contact occurrence rather than dynamic interaction frequency.

---

##  Scientific Background
Acetylcholinesterase (AChE) is a key enzyme involved in the breakdown of acetylcholine.  
Donepezil is a reversible AChE inhibitor commonly used in the treatment of Alzheimer’s disease.

Residues within **4 Å** of a ligand are generally considered part of the **binding pocket** and have a high potential to participate in:
- π–π stacking interactions
- Hydrogen bonding
- Hydrophobic interactions
- van der Waals contacts

---

##  Tools & Technologies
- **PyMOL** – structural visualization and contact selection  
- **Python** – data analysis  
- **Pandas** – data manipulation  
- **Matplotlib** – visualization  
- **Jupyter Notebook** – interactive analysis  
- **Git & GitHub** – version control

---

## Methodology

### 1. Structure Preparation
- AChE–Donepezil complex structure was loaded into PyMOL.
- Protein and ligand were separated into distinct selections.

### 2. Contact Identification (PyMOL)
- Amino acid residues within **4 Å** of Donepezil were selected.
- Atomic-level contacts were extracted.
- Contact data were exported as a CSV file.

### 3. Data Analysis (Python)
- Duplicate residues were handled appropriately.
- Contact frequency per residue was calculated.
- Residues were ranked based on the number of atomic contacts.

### 4. Visualization
- The **Top 15 interacting residues** were visualized using a bar chart.
- Results highlight residues with the highest interaction potential.

---

## Key Results
- Multiple **aromatic residues** (e.g., TRP, PHE, TYR) show high contact frequencies.
- These residues are consistent with known AChE binding pocket characteristics.
- Contact frequency provides a simple but effective proxy for interaction strength.

---

## Conclusions
This project demonstrates a simple and reproducible workflow for:
- Identifying ligand–protein interactions
- Extracting structural data from PyMOL
- Performing quantitative analysis in Python

---

## Author
**Kübra Yılmaz**  
Chemistry Student – Marmara University  



