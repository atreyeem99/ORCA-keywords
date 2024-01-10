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
- `RIJCOSX`approximations made for large molecules
- `D3` or `D4` In general it is advisable to use the D3 or the charge-dependent D4 corrections. These will correct both the energies and gradients and lead to much better results.
- `KEEPDENS` to keep the basename.scfp density file, which will later be used to plot the density
- `TEMP` for mentioning the temperature at which the property is to be measured
- `BOHRS` for correcting the units in the input file
- `Polar 1` means that the polarizability is computed analytically
- `SCALFREQ` These are empirical factors that can be used to multiply all frequencies and correct for errors from theory 
- `DOSOC` for performing spin orbit coupling
