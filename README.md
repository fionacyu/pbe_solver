# pbe_solver
This repository contains relevant structures, input files, timing data used to assess the performance of the EXESS PBE solver compared to DelPhi and AMBER's pbsa.cuda.

`pl_performance_accuracy.csv`: contains timing and solvation energies predicted with EXESS, DelPhi and AMBER

`pl_systems_pb_paper.zip`: contains pdb files for all protein-ligand systems utilised

`amber_pl2.in`: input parameter file used for AMBER pbsa.cuda calculations

`delphi_param.in`: representative input parameter file used for DelPhi calculations

`minnesota_energies.csv`: solvation energies of the Minnesota dataset calculated with EXESS, DelPhi and AMBER
