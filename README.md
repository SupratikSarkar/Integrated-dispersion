# Integrated dispersion

This repository is used to calculate the integrated dispersion of a microring resonator from a given waveguide cross-sectional geometry. 

The repository contains 3 files:

1. _waveguide_dispersion.lms_ : This Lumerical MODE file is used to calculate the waveguide dispersion in units of ps/nm/km.
2. _Dispersion_with_cladding_1200x800nm.txt_ : This text file contains the dispersion in ps/nm/km for a 1200x800nm silicon nitride waveguide with silicon dioxide cladding.
3. _Integrated dispersion.ipynb_ : This python notebook is used to calculate the integrated dispersion in GHz from the data in the text file. The calculation was done up to the 4th order term according to the formulas in [arXiv:2001.00650](https://arxiv.org/abs/2001.00650).
