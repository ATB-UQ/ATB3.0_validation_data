# ATB3.0 validation data
Supplementary data for "The Automated Topology Builder Version 3.0 (ATB3.0):
Prediction of Solvation Free Enthalpies in Water and Hexane."

**The data has been organised as follows:**
- molecules: directory containing subdirectories (ATB_ID) for each molecule included in this work.
    - ATB_ID: directory of molecule data: 3D coordinates (.pdb), building block file in GROMOS format (.mtb),
    calculated and experimental data (molecule.json), 2D drawing (molecule.pdb, molecule.svg).
- 54a7_ATB.ifp: force field parameters in the GROMOS format.
- all_data.json: combined calculated and experimental data used in this work in a dictionary-based data structure.
- experimental_data.csv: all experimental solvation data considered as part of this work.
- TI_data.csv: all calculated solvation results.
