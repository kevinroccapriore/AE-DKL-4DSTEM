# AE-DKL-4DSTEM
Autonomous experimentation via deep kernel learning (DKL)
The following notebook and data demonstrates the use of DKL in scanning transmission electron microscopy (STEM), by effectively utilizing multidimensional signals learning structure-property relationships in the system under study.
Here, the full structural signal from the HAADF-STEM image is combined with 4D-STEM data, i.e., local diffraction imaging.
Using DKL, this generates a structure-property relationship between local image patches (in HAADF) and the diffraction pattern originating from the center of that image patch.

Physics is embedded into this active learning process by scalarizing the diffraction pattern by the method of choice. For example, from the 2D diffraction image, the center of mass (CoM) shift is frequently calculated to provide a measure of beam displacement due to (atomic) electric fields. More complex scalarizers and mathematical operations may be used to incorporate the desired physics of interest, for instance, 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinroccapriore/AE-DKL-4DSTEM/blob/main/AE_4DSTEM_DKL.ipynb)
