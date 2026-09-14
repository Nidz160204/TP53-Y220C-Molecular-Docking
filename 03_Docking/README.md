# Molecular Docking

## Docking Software

Molecular docking was performed using AutoDock Vina 1.2.7.

## Receptor

**Target:** TP53 Y220C mutant  
**PDB ID:** 2VUK

The prepared receptor structure was used as a rigid receptor during docking.

## Ligands

Three ligands were docked against the TP53 Y220C mutant:

- P83 (PhiKan083)
- PK7088
- Rezatapopt (PC14586)

## Docking Parameters

| Parameter | Value |
|---|---|
| Docking software | AutoDock Vina 1.2.7 |
| Receptor | 2VUK |
| Grid center X | 124.684 Å |
| Grid center Y | 105.122 Å |
| Grid center Z | -43.122 Å |
| Grid size | 16 × 16 × 16 Å |
| Exhaustiveness | 16 |
| Number of modes | 9 |

## Docking Workflow

TP53 Y220C receptor
→ Ligand preparation
→ Binding-site definition
→ AutoDock Vina docking
→ Binding-affinity comparison
→ Interaction analysis using PyMOL

## Output

The docking output files contain the predicted binding poses and docking scores for each ligand.
