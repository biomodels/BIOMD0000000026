# BIOMD0000000026: Markevich2004_MAPK_orderedelementary

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000026.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000026.git@20140916`


# Model Notes


The model corresponds to the schemas 1 and 2 of Markevich et al 2004, as
described in the figure 1 and the supplementary table S1. Phosphorylations and
dephosphorylations follow distributive ordered kinetics. The phosphorylations
are modeled with three elementary reactions:  
E+S<=>ES->E+P  
The dephosphorylations are modeled with five elementary reactions:  
E+S<=>ES->EP<=>E+P


