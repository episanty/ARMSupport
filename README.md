ARMSupport
==========
A support suite for Analytical *R*-Matrix calculations.

© Emilio Pisanty 2014-2016

This package provides functions for an implementation of the Analytical *R*-Matrix theory of photoionization (ARM), including detailed handling of integration contour paths for correct navigation of branch cut landscapes where relevant.

The ARM theory is comprehensively developed in the papers

> - L. Torlina and O. Smirnova, Time-dependent analytical R-matrix approach for strong-field dynamics. I. One-electron systems. [*Phys. Rev. A* **86**, 043408 (2012)][Torlina1].
> - L. Torlina, M. Ivanov, Z. B. Walters, and O. Smirnova, Time-dependent analytical R-matrix approach for strong-field dynamics. II. Many-electron systems. [*Phys. Rev. A* **86**, 043409 (2012)][Torlina2].

  [Torlina1]: http://dx.doi.org/10.1103/PhysRevA.86.043408
  [Torlina2]: http://dx.doi.org/10.1103/PhysRevA.86.043409

as well as my MRes report,

> - E. Pisanty, MRes report, *Under-the-barrier electron-ion interaction during tunnel ionization*, Imperial College London, 2012, [arXiv:1307.7329][PisantyMResArXiv].

  [PisantyMResArXiv]: http://arxiv.org/abs/1307.7329

The handling of the integration contour path to avoid branch cuts where they are present is described in detail in

> - Emilio Pisanty, Misha Ivanov, Slalom in complex time: emergence of low-energy structures in tunnel ionization via complex time contours. [*Phys. Rev. A* **93**, 043408 (2016)][PisantySlalom], [arXiv:1507.00011][PisantySlalomArXiv].

  [PisantySlalom]: http://dx.doi.org/10.1103/PhysRevA.93.043408
  [PisantySlalomArXiv]: http://arxiv.org/abs/1507.00011


This package consists of the Mathematica notebook `ARMSupport.nb`, and the auto-generated package file `ARMSupport.m`. For guidance on its use, see the implementations that use the package, which include

> - E. Pisanty, [Figure-maker code for *Slalom in complex time: emergence of low-energy structures in tunnel ionization via complex time contours* and *Kinematic origin for near-zero energy structures in mid-IR strong field ionization* (2016)][SlalomFigureMaker].

[SlalomFigureMaker]: http://dx.doi.org/10.5281/zenodo.46912

This package is dual-licenced under the GPL v3 and the CC BY-SA 4.0 licenses; for the full text see the file `License.txt`. If you use this software package in work that results in an academic publication, you are academically (though not legally) obliged to cite it. An example citation is

> - E. Pisanty. ARMSupport: A support suite for Analytical *R*-Matrix calculations. https://github.com/episanty/ARMSupport (2016).

You should also cite at least one of the papers listed above.
