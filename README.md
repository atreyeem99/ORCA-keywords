# ORCA-keywords
- `PAL` to run parallel calculation
- `OPT` for optimization
- `TIGHTOPT` or `VERYTIGHTOPT` for tightly optimizing structures
- `FREQ` To calculate vibrational frequencies
- `NUMFREQ` for numerical Hessian calculation
- `LARGEPRINT` to generate orbotal plots
- `AUTOAUX` is used when correlated method can be obtained without special basis set
- `NROOTS`
- `%MAXCORE n` for increasing memory; n is the value of the increase
- `NUMGRAD` is used when you want to optimize the geometry for a method for which no analytical gradient is available. But this takes longer time for calculation.
- `TightPNO` is used for steom calculations
- `TightSCF` for tight convergence
- `DONTO` for plotting NTOs
- `ZORA` including relativistic correlation
- `EXTRAPOLATE(3)` 3 calculations using the basis set from the family cc-pVxZ; then CBS result extrapolated
- `IRC` is a special form of a minimum energy path, connecting a transition state (TS) with its downhill-nearest intermediates. A method determining the IRC is thus useful to determine whether a transition state is directly connected to a       given reactant and/or a product.
- `RIJCOSX`approximations made for large molecules in TDDFT calculations.
- `RIJONX` RI approximations made in SCF calculations
- `D3` or `D4` In general it is advisable to use the D3 or the charge-dependent D4 corrections. These will correct both the energies and gradients and lead to much better results.
- `KEEPDENS` to keep the basename.scfp density file, which will later be used to plot the density
- `TEMP` for mentioning the temperature at which the property is to be measured
- `BOHRS` for correcting the units in the input file
- `Polar 1` means that the polarizability is computed analytically
- `SCALFREQ` These are empirical factors that can be used to multiply all frequencies and correct for errors from theory 
- `DOSOC` for performing spin orbit coupling
- `riints` RI approximation(MO)
- `riints_disk` faster
- `PARAS` Input of semi-empirical parameters
- `DoAlpha` Removal/addition of alpha electrons
- `DoBeta ` Removal/addition of beta electrons
- `COORDS` Input of atomic coordinates
- `LOC` For localization of orbitals
- `symmetry` Control of spatial symmetry recognition
- `REL` Control of relativistic options
- `ROCIS` Control of restricted-open-shell CIS
- `ANGS` Selects Angstorm units
- `noiter` in order to turn o↵ the standard Hartree-Fock SCF process before entering the orbital optimizations.
- `rocis` Control of restricted-open-shell CIS
- `EnGrad` specifying ’density relaxed’ is unnecessary. However, it is needed when calculating properties without the gradient.
- `SymRelaxSCF` Indicates whether orbital occupation numbers of each irreducible representation are allowed to change during SCF
- `PRINTGAP` Prints the HOMO/LUMO gap in each SCF iteration. This may help to detect convergence problems
- `PRINTMOS` Prints MO coeffecients
- `NOPRINTMOS` Suppress printing of MO coefficients
-  `XYZFILE`  Produce an XYZ coordinate file
-  `PDBFILE`  Produce a PDB file
-  `Printbasis` Print the basis set in input format.
-  `FLOAT` Set storage format for numbers to single precision (SCF, RI-MP2, CIS, CIS(D), MDCI
-  `UNO` Produce UHF natural orbitals
-  `ACCURACY` accuracy, value for --acc, default is ORCA’s accuracy x 1.e6
-  `MaxDim 3` Davidson expansion space = MaxDim * NRoots
-  `ALPB(water)` use implicit solvation, solvent water,  ALPB with water  can also be defined in the xtb block
-  `orbOpt true` turns on the orbital optimization
-  `ALLPOP` Turns on all population analysis
-  `MULLIKEN` turns on the Mulliken analysis
-  `Loewdin` Turns on the Loewdin analysis
-  `Noloewdin` Turns off the Loewdin analysis
-  `PATOM` Selects the polarized atoms guess
-  `HUECKEL` Selects the extended Hückel guess
-  `DecontractAuxJ` Decontract the AuxJ basis set
-  `UCFLOAT` Use float storage in the matrix containers without data compression
-  `NORMALPRINT` Selects the normal output
-  `CHEAPINTS` Use the cheap integral feature in direct SCF calculations
-  `NOCHEAPINTS` Turn that feature o↵
-  `READINTS` Reading of two electron integrals on
-  `AIM` Produce a WFN file
-  `MAYER` Turns on the Mayer analysis
-  `NOMAYER` Turns off the Mayer analysis
-  `RR` Control of resonance Raman and absorption/fluorescence band-shape calculations
-  `REL` Control of relativistic options
- `EPRNMR` Control of EPR and NMR calculations
- `PLOTS` Control of plot generation
