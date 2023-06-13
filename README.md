# WavesOnModulation
Solver for waves in a spring-mass lattice with a progressive periodic modulation 

## Contents
* ``mainWPPM.ipynb`` contains numerical tools in support of a draft available on arxiv (see below).
* In particular: it contains
* an implicit (somewhat sparse, also elementary) Runge-Kutta solver
* pre-defined Butcher tableaux for symplectic Radau 6 and Gauss-Legendre 6

## Notes
* Tested on a Macbook pro (2018, i7, 16gb)
* In some cases, semi-implicit methods are far more efficient and should be preferred: see references below

## Dependencies
* ``numpy`` and ``scipy``
* ``matplotlib'' for plotting

## References
* https://arxiv.org/pdf/2211.06294.pdf
* http://bison.ihep.su/~kachaev/books/ode/yoshida_const_higher_order_symplectic_integ_1990.pdf
