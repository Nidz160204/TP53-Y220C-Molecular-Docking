# Molecular Docking

## Overview

Molecular docking was performed to investigate the predicted binding of P83, PK7088 and Rezatapopt to the TP53 Y220C mutant.

Docking was performed using AutoDock Vina 1.2.7.

## Docking System

- **Receptor:** TP53 Y220C mutant
- **PDB ID:** 2VUK
- **Ligands:** P83, PK7088, Rezatapopt
- **Docking software:** AutoDock Vina 1.2.7

## Docking Files

- `P83_vina.log` – AutoDock Vina docking output for P83
- `PK7088_vina.log` – AutoDock Vina docking output for PK7088
- `Rezatapopt_vina.log` – AutoDock Vina docking output for Rezatapopt
- `vina_config.txt` – Docking configuration and search parameters

## Workflow

1. Prepared the TP53 Y220C receptor in PDBQT format.
2. Prepared the ligand structures for docking.
3. Performed molecular docking using AutoDock Vina.
4. Selected the best-scoring docking poses for downstream analysis.
5. Visualized the predicted binding interactions using PyMOL.
