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
- `ELPROP` Control of electric property calculations
- `MCRPA` Control CASSCF linear response calculations
- `CIM` Control of Cluster In Molecules calculations
- `CIPSI` Control of Iterative-Configuration Expansion Configuration Interaction calculation
- `AUTOCI` Controls autogenerated correlation calculations
- `PLOTS` Control of plot generation
- `NMRSpectrum true` request simulation of NMR spectrum
- `UNIT` The flag UNIT can be used to control the output unit of the X axis. Its values can be CM-1, NM or EV and it only a↵ects the OUTPUT, the INPUT should always be in cm 1
- `SPLITJ` Select the efficient Split-J procedure for the calculation of the Coulomb matrix in non-hybrid DFT (rarely used)
- `RI-JK` Sets the flag for the efficient RI algorithm for Coulomb and Exchange. Works for SCF (HF/DFT) energies and gradients. Works direct or conventional.
- `SPLIT-RI-J` Select the efficient Split-RI-J procedure for the improved evaluation of the RI- approximation to the Coulomb-matrix
- `NoSplit-RI-J` Turns the Split-RI-J feature o↵ (but does not set the RI flag to false!)
- `RI-J-XC` Turn on RI for the Coulomb term and TRIX,RI the XC terms. This saves time when the XC integration is significant but intro-duces another basis set incompleteness error. (rarely used)
- `PATOM` Selects the polarized atoms guess
- `PMODEL` Selects the model potential guess
- `decorr` for double hybrid functional
- `FIC-DDCI3` Fully internally contracted DDCI3
- `SORCI` Spectroscopy oriented CI
- `AUTOSTART` Try to start from the existing GBW file of the same name as the present one (only for single-point calculations)
- `IORAmm/RI`Selects the scalar relativistic IORA mm (modified metric) Hamiltonian in RI approximation
- `STRONGSCF` Selects strong SCF convergence
- `ForceConv` Force convergence: do not continue with the calculation, if the SCF did not fully converge.
- `IgnoreConv` Ignore convergence: continue with the calculation, even if the SCF wavefunction is far from convergence.
- `SlowConv` Selects appropriate SCF converger criteria for difficult cases. Most transition metal complexes fall into this category.
- `EasyConv` Assumes no convergence problems.
- `VerySlowConv` Selects appropriate SCF converger criteria for very difficult cases.
- `SOMF(1X)` Invokes the SOMF(1X) treatment of the spin-orbit coupling operator.
- `RI-SOMF(1X)` Invokes the SOMF(1X) treatment of the spin-orbit coupling operator, with RI four the Coulomb part.
- `VEFF-SOC` Invokes the VEFF-SOC treatment of the spin-orbit coupling operator.
- `AMFI` Invokes the AMFI treatment of the spin-orbit coupling operator.
- `AMFI-A` Invokes the AMFI-A treatment of the spin-orbit coupling operator.
- `ZEF-SOC` Uses e↵ective nuclear charges for the spin-orbit coupling operator.
- `modetype normal` normal modes of vibration: PES
- `MList` provides the list of the normal modes to be scanned.
- `RSteps and LSteps` specify the number of steps in positive and negative direction along each mode in the list.
- `HessName` parameter specifies the name of the file which contains nuclear Hessian matrix calculated in the frequency run.
- `DOHT TRUE` here, because the first transition of benzene is symmetry forbidden with an oscillator strength of 2e-6 and thus all the intensity comes from vibronic coupling
- `ESD(FLUOR)` Fluorescence rate calculation
- `LINEW` It is common that the experimental lineshape changes depending on the set up and it can be controlled from the LINEW flag
- `VOIGT` The default lineshape for resonant Raman is VOIGT.
- `SPECRES` The resolution of the spectrum can be modified with the SPECRES flag.
- `DELTA` lineshape might lead to a correlation function that oscillates forever, so please take care with that option.
- `PRINTLEVEL` can be set to HIGH in order to print more details. 1,2,3,4
- `ESD(PHOS)` phosphorescence calculation
- `ESD(ISC)` intersystem crossing calculation
-`RI-SOMF(1X)` option for the spin-orbit coupling integrals, but any of the methods available can be used
- `SROOT` and `TROOT` you can control the SROOT and TROOT flags to select which are the singlet and triplet you want to compute
- `RRSLINEW` The spectral linewidth in this case is independent (but not the lineshape) and must be set with the RRSLINEW keyword, being 10 cm 1 by default.
- `Delta` The DELTA lineshape might lead to a correlation function that oscillates forever, so please take care with that option.
- `FASTDER` Use the fast derivatives algorithm?
- `Random`Always take the same seed for start for localization
- `TDIP` ustom transition dipole
- `USEJ` Consider Duschinsky rotations
- `USEB` Rotate the initial state?
- `LASERE` The laser energy for RR
- `DELRE` Custom energy difference
- `TDIP` Custom transition dipole
- `COORSYS` Coordinate system for the normal modes
- `GEOMSTEP` geometry step
- `STEPSCALING` A number for scaling the steps
- `STEPCONSTR` A list of atoms that will not be moved
- `sTDA` Use sTDA during derivatives
- `sameFrreq` use DO method and J=1.
- `UF_DELE` Energy difference for updated freq.
-`CONVDER` Convert derivatives between state
- `Lines` The lineshape function
- `SCALING` caling for frequencies
- `MO("CO-4.plt",4,0)` is to be understood as follows: there is an MO to be evaluated on a grid and the output is stored in the file ”CO-4.plt”.
- `Skeleton` Draw Skeleton of the molecule of those atoms that are in or close to the cut
- `VIRT` Localize the virtual space
- `TOL` absolute convergence tolerance for the localization sum
- `T_Bond` Thresh that classifies orbitals in bond-like at the printing
- `T_Strong` Thresh that classifies orbitals into strongly-localized at the printing
- `OCC` Localize the occupied space
- `NMRREF[X]` Reference value for the absolute shielding of element X used in the relative shifts of the simulated spectrum.
- `NMRCoal` If two lines are closer than this threshold (given in Hz) then the module will coalesce the lines to one line with double intensity. threshold for merged lines [Hz] (default 1)
- `NMRSpecFreq` The NMR spectrometer frequency is decisive for the looks of the spectrum as shieldings are given in ppm and couplings are given in Hz.
- `NMREquiv` lists of NMR-equicalent nuclei
- `Decontract` Decontract all (orbital and auxiliary) basis sets
- `EXTREMESCF` Selects “extreme” convergence. All thresholds are practically reduced to numerical precision of the computer. Only for benchmarking (very expensive).
- `SCFCONVn` Selects energy convergence check and sets ET ol to 10 n (n = 6–10). Also selects appropriate thresh, tcut, and bfcut values.
- `LOOSEOPT` Selects loose optimization convergence
- `KDIIS` Turns Kollmar’s DIIS on
- `TRAH` Turns trust-region augmented Hessian SCF on
- `SOSCF` Turns SOSCF on
- `NOLSHIFT` Turns level shifting o↵
- `CIM` Cluster-In-Molecule calculation
- `MD` Molecular dynamic simulation
- `UseSym` Turns on the use of molecular symmetry (see section 6.6). THIS IS VERY RUDIMENTARY! 
- `FOD` FOD analysis (see 9.7.8.2) employing default settings (TPSS/def2-TZVP,TightSCF, SmearTemp = 5000 K)
- `CIM` Cluster-In-Molecule calculation
- `MP2` Selects Method=HF and DoMP2=true
- `SCS-MP2` Spin-component scaled MP2
- `COPT` Optimization in Cartesian coordinates
- `GDIIS-COPT` COPT using GDIIS
- `MP2-F12` MP2 with F12 correction
- `CEPA/1` Coupled-electron-pair approximation
- `DecontractBas` Decontract the basis set. If the basis set arises from general contraction, duplicate primitives will be removed.
- `IORA/RI` Selects the scalar relativistic IORA Hamiltonian in RI approximation
- `NOFINALGRIDX` Turn o↵ the final grid in COSX (not recommended)
- `NOTRAH` Turns trust-region augmented Hessian SCF off
- `VEFF-SOC` Invokes the VEFF-SOC treatment of the spin-orbit coupling operator.
- `AMFI` Invokes the AMFI treatment of the spin-orbit coupling operator.
- `AMFI-A` Invokes the AMFI-A treatment of the spin-orbit coupling operator.
- `ZEFF-SOC` Uses e↵ective nuclear charges for the spin-orbit coupling operator.
- `FRACOCC` Turns the fractional occupation option on (FOD is always calculated in this case)
- `NBO` Turns on the interface for the NPA plus NBO analysis with the GENNBO pro- gram
- `NOSMEAR` Turn occupation number smearing off
- `DKH` Selects the scalar relativistic Douglas– Kroll–Hess Hamiltonian of 2nd order
- `Decontract` Decontract all (orbital and auxiliary) basis sets
- `CDOUBLE` Use double storage in the matrix containers with data compression
-  VerySlowConv` Selects appropriate SCF converger criteria for very difficult cases.
-  `NoTrah` Turns trust-region augmented Hessian SCF off
-  `SCS-PBE-QIDH` spin-component scaled version of PBE-QIDH optimized for excited states by Casanova-Páez and Goerigk (SCS only applies to the CIS(D) component)
- `wB97X-D2` Chai and Head-Gordon’s wB97X-2(TQZ) range-separated GGA-based DHDF with spin-component scaling
- `nprocs` processors
- `Zoom-NEB (Z-NEB)` method has been included this implementation, where the objective of the method is to locate a saddle point more accurately with a better resolution compared to CI-NEB calculations.
- `CI-NEB` calculation is carried out to obtain a rough convergence towards the MEP
- `LOOSE-NEB-TS` corresponds to the actual NEB-TS defaults,
- `EW-CI-NEB` method is used to partially converge to the MEP and hence saddle point, i.e., the optimization of the images along the MEP is halted once the climbing image is converged to a prescribed tolerance.
- `Almlöf` Hessian matrix is used, the curvature at the CI is estimated by using a finite diverence approximation
- `IDPP_ksp` spring constant used to scale the spring force parallel to the path.
- `IDPP_Alpha` multiplicative factor to scale the size of the step ineach opt. cycle
- `IDPP_ksp`  spring constant used to scale the spring force parallel to the path.
- `EThresh value` Energy threshold up to which CSFs are included (in eV)
- `Beta1 value` Constant part of J integral parameter beta
- `triplets true` Calculate singlet-triplet excitations (default: singlet-singlet)
- `alpha1 value` Constant part of K integral parameter alpha
- `PTLimit Value` Energy threshold up to which CSFs beyond EThresh may be selected (in eV)
- `NEB-IDPP` IDPP (Initial Path) NEB calculation - for estimation of path length
- `NPTS_Interpol` Number of abscissa in cubic polynomial interpolation
- `Free_End false` se free-end NEB. In this case the NImages corresponds to the total number of images.
- `Fix_center True Fix_center specifies whether the centroid of each image should be constrained to the origin of the coordinate system or to the center of each image individually.
- `Mode sTDA` Invokes a sTDA calculation
- `axstda` Fock exchange parameter used in sTDA/sTD-DFT calculation (for range-separated hybrids)
- `ICE-CI` is either a highly robust high accuracy method for very small systems or a “building block” for large systems
- `ICE-CI method is extremely parallel to the full CI curve at all distances.
- `UseMP2nat` The use of MP2 natural orbitals is requested by choosing UseMP2nat true inside the %ice block.
- `AUTOCI` module is a replacement of the orca mdci for cases, where manual implementation of the method would be tedious or practically impossible.
- `RHF, ROHF, UHF and CASSCF` and offers CI and related methods.
- `(FIC-MRCI)` uses the same internal contraction scheme as the FIC-NEVPT2 (aka PC-NEVPT2).
- `In case of ACPF and AQCC` the lambda factor explicitly depends on the number of correlated electrons, Ne .
- `The fic-MRCC` module can be started by specifying the CIType keyword in the %autoci block or by adding fic-MRCC to the simple input line of an ORCA
- `casscf_nel` 6 number of active space electrons
- `casscf_weights[0]` = 0.5,0.2,0.2,0.2 # singlet weights
- `casscf_mult` 1,3 multiplicities singlet and triplet
- `FOD` analysis (see Fractional Occupation Number Weighted Electron Density (FOD)) employing default settings (TPSS/def2-TZVP, TightSCF, SmearTemp = 5000 K)
- `L-SR1` is set by default for DeltaSCF
- `NWORKERS AUTO` # define the number of workers (default AUTO).AUTO for an automatic ideal assignment, or give any number multiple of 4 (number of temperatures).
- `FREEHETEROATOMS FALSE` # free all atoms besides H and C.
- `QDPT` properties. These are properties that are calculated by quasi-degenerate perturbation theory (QDPT).
- `bt-PNO-EOM-CCSD` back-transformed PNO approximation
- `TNOSCALES` 10.0 #TNO truncation scale for strong triples, TNOSCALES*TCutTNO. Default setting is 10.0
- `orca_prop` Calculation of molecular properties
- `QUICKDOCK` simple keyord to set DOCKLEVEL QUICK
- `LINEW and INLINEW` control the LINES function used in the calculation of the correlation function and are related to the lifetime of intermediate states and energy disordering.
- `orca_cclib` Precalculation of one particle coupling coefficients for ACCCI
- geometry used in the input file should correspond to that of the FINAL state, specified through the `ISCFSHESSIAN` flag
- You can select any of the methods described earlier to obtain the Potential Energy Surface (PES) by setting the appropriate `HESSFLAG`
- `casscf_nroots 4,2` # four singlets, two triplets
- `casscf_weights[0] ` = 0.5,0.2,0.2,0.2 # singlet weights
- `casscf_weights` = 0.7,0.3 triplet weights
- `casscf_mult 1,3` multiplicities singlet and triplet
- `casscf_norb 6` number of active orbitals
- `casscf_bweight 2,1` # singlets and triplets weighted 2:1
- `Mult 3` multiplicity of PES2
- `soln25` index of refraction at optical frequencies at 298 K
- `sola` # Abraham’s hydrogen bond acidity
- `PartialGCFlag -1`  Let the program decide whether to use PGC
- `RIJFlag RIJ_Auto` default: program decides the best way
- `FockFlag SHARK_libint_hybrid` # default: best of both worlds
- `PartialGCFlag -1` Let the program decide whether to use PGC
- `Split_rij` new SHARK Split-RI-J algorithm
- `Split_rij_2003` Highly efficient re-implementation of the Original 2003 algorithm. Mostly used!
- `rij_regular` Use traditional 3 center integrals
- `force_shark` Force Shark where possible
- `force_libint` Force libint where possible
- `Printlevel 1` Amount of output generated. Choose 0 to suppress output and 2 for more output.Everything else is debug-level printing and will fill your harddrive very quickly with unusable information
- `PartialGCFlag 1` Enforce PGC (even for ANO bases)
- `UseGeneralContraction false turns general contraction algorithm on or off.There normally is no need to set this flag since the program will find the contraction case automatically
- `Excitations cisd` Type of excitations
- `Refs CAS(NEl,NOrb) end` Reference space def.
- `useivos false` use improved virtual orbitals
- `useMP2nat false` use MP2 natural orbitals
- `useQROs false`  For UHF: use quasi-restricted MOs?
- `integrals exact`  exact or ri transformation
- `diisstartiter 2 ` Apply DIIS starting at iteration 1
- `trafotype 0`  Type of integral transformation
- `trafotype 0 `Type of integral transformation
- `useoldints ` Use the transformed integrals found on disk
- `keepints ` Keep the transformed integrals on disk
- `diisstartiter 2 ` Apply DIIS starting at iteration 1
- `FICMRACPF ` Fully internally contracted ACPF
- `FICDDCI3` FIC-MRCI without the IJAB excitation
- `CEPA0` linearized CCSD
- `FICMRAQCC` Fully internally contracted AQCC
- `stol` 1e-06 # residue convergence tolerance
- `citype` Type of the CI expansion to be applied (one of following)
- `FICMRCEPA0 ` Fully internally contracted CEPA0
- `FICDDCI3` FIC-MRCI without the IJAB excitation
- `irrep 0`  requested irrep for mult block
- `D3TPre` 1e-14 # Density truncation in D3
- `irrep 0` # requested irrep for mult block
- `LINEARIZED` Linear part of the density
- `UNRELAXED` Unrelaxed 1-body density matrix
- `NONE` No density calculation
- `density` type of density requested
- `nthresh 1e-6` removal of linear dependencies in the IC-CS
- `%moinp "start.gbw" ` could be from CASSCF
- `DavidsonOpt 0  none (default)` Davidson correction for the FIC-MRCI
- `TS_Mode {D 3 2 1 0} end ` dihedral of atoms 3, 2, 1 and 0
- `TS_Mode {A 2 1 0} end` angle between atoms 2, 1 and 0
- `{ B N1 N2 value C }`the bond between N1 and N2
- `{ D * * * * C }` all dihedrals
- `{ B 10 0 A }` add a bond between atoms 0 and 10
- `{ A 8 9 10 R }` remove the angle defined by atoms 8, 9 and 10
- `TS_Mode {A 2 1 0}` end angle between atoms 2, 1 and 0
- `{ A 8 9 10 R }` remove the angle defined by atoms 8, 9 and 10
- `{ D * * * * C }` all dihedrals
- `{ C N1 C }` the cartesian position of N1
- `{ B * * C}` all bonds
- `{ D 7 8 9 10 R } ` remove the dihedral angle defined by atoms 7, 8, 9 and 10
- `{ A N1 N2 N1 value C }` the angle defined by N1, N2 and N3
- `TS_Mode {D 3 2 1 0}` end  dihedral of atoms 3, 2, 1 and 0
- `{ B N1 * C}` all bonds involving N1
- `fullScan true` if !ScanTS is requested, fullScan assures that the relaxed surface scan is fully carried out before the TS optimization is started (Default is false)
- `{1 2 C}` constrain the internal coordinates connecting fragments 1 and 2
- `{1 3 O}` optimize the internal coordinates connecting fragments 1 and 3
- `Scan B N1 N2 [value1 value2 value3 ... valueN] end` perform constrained optimizations with N1-N2-distances
- `GDIISMaxE`  number of last steps to use in GDIIS algorithm
- `GDIISStart 1.0 ` Gradient at which to start GDIIS algorithm
- `MaxStep 0.3 ` maximum step length in internal coordinates. Default is 0.3 au
- `TolRMSG 1e-4` RMS gradient (a.u.)
- `TolMaxG 3e-4 ` Max. element of gradient (a.u.)
- `TolMaxD 4e-3 ` Max. displacement (a.u.)
- `UseGDIIS false ` use GDIIS step (in Cartesian optimization)
- `GDIISMaxE 10`  number of last steps to use in GDIIS algorithm
- `ProjectTR false ` project translation and rotation
- `MaxStep 0.3 ` maximum step length in internal coordinates. Default is 0.3 au
- `Trust -0.3 ` Initial trust radius. Default is -0.3 au
- `reset 5 ` reset the modified internal Hessian values after 5 cycles
- `XYZ1 "scanName.003.xyz" ` the xyz-files of the structures
- `XYZ2 "ScanName.005.xyz" ` next to the highest energy point
- `GBW1 "ScanName.003.gbw" ` the gbw-files of the structures
- `GBW2 "ScanName.005.xyz" ` next to the highest energythe gbw-files are optional
- `ReducePrint true `reduce printout after the first point default=true
- `OptGuess= OneElec ` the one electron matrix
- `UseSOSCF false ` switches the converger to SOSCF after the first point.
- `NResetHess 20 ` Set the number of geometry steps after which a new model Hessian is built
- `FICMRACPF` Fully internally contracted ACPF
- `FICMRAQCC` Fully internally contracted AQCC
- `Trust -0.3 ` Initial trust radius. Default is -0.3
- `TolRMSD 2e-3 ` RMS displacement (a.u.)
- `TolMaxD 4e-3`  Max. displacement (a.u.)
