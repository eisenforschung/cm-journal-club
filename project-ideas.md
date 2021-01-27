- (2020/12/09) Creation of spin dynamics module on pyiron (cf. [notebook](https://github.com/eisenforschung/cm-journal-club/blob/master/2020-12-16/spin-dynamics.ipynb))
  - Separate the time integration and the Hamiltonian, so that the Hamiltonian can be defined by the user and inserted in the spin dynamics algorithm
  - Do a comparison between MC and SD -> results should be given in terms of physics as well as convergence speed.
  
- (2021/01/13) Effect of H on vacancy formation in bcc Fe (cf. [notebook](https://github.com/eisenforschung/cm-journal-club/blob/master/2021-01-11/fe-h.ipynb))
  - How does the slab method compare to thermodynamic integration results?
  - How to make a stable algorithm to determine what is considered as surface and what is bulk.
  - How does the simulation time affect the vacancy concentration?
  - Measure chemical potentials of H in bulk, surface and vacuum.
  - Measure vacancy formation free energy as a function of the H to simulate hydrogen charging.
