# Molecular Analysis with RDKit

## Overview
This project explores the use of RDKit in conjunction with Python to analyze molecular structures. Selected molecules, including Propane, Ethene, Cyclohexane, and Buckminsterfullerene (C60), are studied to determine atom counts, atomic weights, and the number of aromatic bonds. Additionally, a subset of compounds from the Delaney solubility dataset is visualized.

## Tools & Libraries
- Python
- RDKit
- Pandas
- Matplotlib
- Seaborn

## Project Tasks
1. **Molecule Creation**
   - SMILES strings were used to create RDKit molecule objects for selected compounds.
   - Molecules included simple organics and complex fullerenes.

2. **Atom & Bond Analysis**
   - Computed the number of atoms in each molecule.
   - Printed the chemical symbol and atomic weight of each atom.
   - Determined the number of aromatic bonds.

3. **Dataset Visualization**
   - Loaded Delaney solubility dataset.
   - Visualized the first six compounds in a molecular grid with compound labels.

4. **Challenges Encountered**
   - Parsing complex SMILES strings like Buckminsterfullerene caused errors in RDKit.
   - Visualization issues with labels for compounds in the molecular grid.
   - Mitigated issues using alternative SMILES strings, try-except handling, and data type conversion.

5. **Potential Improvements**
   - Validate SMILES inputs before processing to reduce parsing errors.
   - Upgrade RDKit or integrate libraries like Open Babel for complex molecules.
   - Enhance visualization with clearer grids, resolution, and color-coded molecular features.
   - Print summary statistics to improve transparency and reproducibility.

## Key Learnings
- RDKit is effective for molecular analysis, but complex molecules require careful SMILES handling.
- Visualization enhances understanding of molecular structures.
- Preprocessing and validation of molecular data is crucial for robust analysis.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook or Python scripts to generate analysis and visualizations.

- `molecular_analysis.ipynb` – Main notebook with analysis workflow.
- `solubility.csv` – Sample dataset used for visualization of molecular compounds.
