# TP53 Y220C Molecular Docking

## Overview

This project investigates the predicted interactions between the TP53 Y220C mutant and three small-molecule compounds — P83 (PhiKan083), PK7088, and Rezatapopt (PC14586) — using molecular docking.

The TP53 Y220C mutant structure was obtained from the Protein Data Bank (PDB ID: 2VUK).

## Objective

The objectives of this project were to:

- Prepare the TP53 Y220C protein structure for molecular docking
- Prepare the selected ligand structures
- Perform molecular docking using AutoDock Vina
- Compare predicted binding affinities of the selected compounds
- Visualize and analyze predicted protein–ligand interactions using PyMOL

## Target Protein

**Protein:** TP53 Y220C mutant  
**PDB ID:** 2VUK

## Ligands

Three compounds were investigated:

1. P83 (PhiKan083)
2. PK7088
3. Rezatapopt (PC14586)

## Tools & Software

- AutoDock Vina 1.2.7
- Meeko
- RDKit
- Open Babel
- PyMOL
- RCSB Protein Data Bank (PDB)
- PubChem

## Methodology

The computational workflow consisted of:

1. Target protein selection
2. Protein structure preparation
3. Ligand selection
4. Ligand preparation
5. Binding-site/grid definition
6. Molecular docking using AutoDock Vina
7. Comparison of predicted binding affinities
8. Protein–ligand interaction analysis using PyMOL

## Docking Parameters

| Parameter | Value |
|---|---|
| Receptor | TP53 Y220C (2VUK) |
| Docking software | AutoDock Vina 1.2.7 |
| Grid center X | 124.684 Å |
| Grid center Y | 105.122 Å |
| Grid center Z | -43.122 Å |
| Grid size | 16 × 16 × 16 Å |
| Exhaustiveness | 16 |
| Number of modes | 9 |

## Results

The best-scoring docking poses were compared for the three compounds.

| Ligand | Predicted Binding Affinity |
|---|---:|
| P83 (PhiKan083) | -5.012 kcal/mol |
| PK7088 | -4.805 kcal/mol |
| Rezatapopt (PC14586) | -4.716 kcal/mol |

Under the docking conditions used in this study, P83 (PhiKan083) produced the most negative predicted binding affinity among the three compounds.

## Interaction Analysis

The best-scoring docking poses were visualized using PyMOL. Protein–ligand contacts within approximately 4 Å of each ligand were examined to characterize the predicted binding environment.

## Key Skills Demonstrated

- Structural bioinformatics
- Molecular docking
- Protein structure preparation
- Ligand preparation
- Protein–ligand interaction analysis
- Molecular visualization
- Computational drug discovery

## Important Note

The docking scores reported in this project are computational predictions and should not be interpreted as experimentally measured binding affinities or definitive evidence of biological activity. Further experimental validation would be required to confirm the predicted interactions.

## Project Context

This project was completed as part of a Bioinformatics internship with **Ediglobe**.

## References

- RCSB Protein Data Bank — PDB ID: 2VUK
- PubChem
- Trott, O., & Olson, A. J. (2010). AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading.
- Eberhardt, J., Santos-Martins, D., Tillack, A. F., & Forli, S. (2021). AutoDock Vina 1.2.0.
