HS13L-Benchmark-Set
This archive contains the coordinates for the HS13L and HS13L-CI (with counterions for complexes 10-13) benchmark test set. 
They are provided in the following way:

The coordinates are provided in the Turbomole format in atomic units and in xyz format.
The respective charges are provided in the .CHRG and an .ORCACHRG file in the respective folder.
the .res files contain: 
1. Theoretical reference values:  “DLPNO-CCSD(T1)/CBS" (see orignial publication for details) in kcal/mol 
for HS13L and HS13L-CI:
.reshs13lccref
.reshs13lciccref
2. Experimental reference values:   backcorrected experimental values at GmRRHO(GFN2[ALPB])-SPH+Gsolv(COSMO-RS16-normal)//r2scan-3c[SMD] level in kcal/mol
for HS13L and HS13L-CI:
.reshs13lciexpref
.reshs13lexpref
