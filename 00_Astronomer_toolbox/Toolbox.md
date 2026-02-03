# Tool box

## Overview
This document compiles several tools and links that are useful for most astronomers. 
This is a living document that may evolve with time. You should feel free to propose tools that are not included in that list but that you think are particularly useful 

## Contents
- VS Code: https://code.visualstudio.com/ 
- TOPCAT: https://www.star.bris.ac.uk/~mbt/topcat/ 
- Aladin desktop: https://aladin.cds.unistra.fr/java/nph-aladin.pl?frame=downloading 
- DS9: https://sites.google.com/cfa.harvard.edu/saoimageds9 
- Qfitsview: https://www.mpe.mpg.de/~ott/QFitsView/ 
- Databases: A list of useful ressources compiling open source codes for specific astronomical tasks 


### VS Code

Not specific to astronomers but a very powerful IDE for developping code. More information and installation: https://code.visualstudio.com/ . This is very complementary to the use of Jupyter Notebooks in a browser or within Jupyterlab (that you can install easily with conda). 
Jupyterlab environment is the interface currently chosen by ESA Datalabs https://datalabs.esa.int/ 

Another powerful IDE is pycharm: https://www.jetbrains.com/pycharm/ . Education licences exist for this tool, expanding its capabilities (see https://lp.jetbrains.com/pycharm-for-students/ and https://www.jetbrains.com/help/pycharm/pycharm-educational.html)

### TOPCAT

A powerful tool for manipulating big catalogs and querying remote databases in an interactive way. 
https://www.star.bris.ac.uk/~mbt/topcat/ . TOPCAT is particularly brilliant when it comes to cross match entries in big catalogs (e.g. millions of objects). Since a few years, there is developement of STILTS (https://www.star.bris.ac.uk/mbt/stilts/) which enables to script actions in TOPCAT and ease repeatability of catalog manipulations and figures in TOPCAT (see also a brief description of STILTS here https://arxiv.org/abs/2501.03299v1)


### Aladin Desktop 

A powerful tool for interactive query and visualisation of data from surveys and from various archives. 
https://aladin.cds.unistra.fr/java/nph-aladin.pl?frame=downloading 
Can interact with TOPCAT through SAMP "protocol". Note that astropy can interact with Aladin Desktop, TOPCAT and DS9 using the SAMP: https://docs.astropy.org/en/latest/samp/example_table_image.html 

### DS9 

An image visualization tool that can overplot catalogs. Several capabilities are similar to Aladin, but since it was originally designed for image visualisation, the catalog query and interactive manipulation is a bit less handy. 

### QFitsview

A powerful fits viewer mostly designed to manipulate Integral Field Spectroscopy data. 

### Databases for CODE 

- Tool for searching public astronomical code: https://code.nasa.gov/ (see also https://arxiv.org/abs/2012.12526 )
- A large Db of public code ASCL.NET: http://ascl.net/ (see also https://arxiv.org/abs/2212.12682 ; which includes tutorial for finding softwares in ascl)
- Astroparticles - Cosmology: community effort to collect all HEP/ASTRO/COSMO open source packages/libraries/tools in one place: https://github.com/nikosarcevic/HEP-ASTRO-COSMO/#hep 
- MULTIMODAL UNIVERSE: https://github.com/MultimodalUniverse/MultimodalUniverse - https://arxiv.org/abs/2412.02527: large-scale multimodal dataset of scientific astronomical data, compiled specifically to facilitate machine learning research. 
- PyCPL: https://www.eso.org/sci/software/pycpl/ - New (2025+) ESO API for data reduction 
- Archival of github softwares: Software Heritage  https://archive.softwareheritage.org 

### Databases for archives 

- ESA Sky: https://sky.esa.int A powerful online portal for querying and visualising public data 
- MAST - Mikulski Archive for Space Telescopes: https://archive.stsci.edu/ 
- VIZIER: most complete library of published astronomical catalogues --tables and associated data https://vizier.u-strasbg.fr/ 
- SIMBAD: Database of (mostly Galactic) astronomical objects: https://simbad.cfa.harvard.edu/simbad/ 
- NED: Nasa Extragalactic Database - https://ned.ipac.caltech.edu/ 
- Virtual Observatory Theoretical model service: https://svo2.cab.inta-csic.es/theory/main/ 
Of particular interest: 
* Transmission curves for (almost) all the filters and instruments: https://svo2.cab.inta-csic.es/theory/fps3/ 
* Theoretical spectra, observational templates of stars and galaxies, Planetary models, ... 
- Best Practice for DataPublication in Astronomical Literature: Chen et al. 2022, ApJS, 260, 5 https://ui.adsabs.harvard.edu/abs/2022ApJS..260....5C/abstract 

Author: Dominique Sluse 