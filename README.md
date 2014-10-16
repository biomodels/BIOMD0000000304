# BIOMD0000000304: Plant1981_BurstingNerveCells

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000304.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000304.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000304 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Bifurcation and resonance in a model for bursting nerve cells. **   
Plant RE _J Math Biol_1981 Jan; 11(1): 15-32
[7252375](http://www.ncbi.nlm.nih.gov/pubmed/7252375),  
**Abstract:**   
In this paper we consider a model for the phenomenon of bursting in nerve
cells. Experimental evidence indicates that this phenomenon is due to the
interaction of multiple conductances with very different kinetics, and the
model incorporates this evidence. As a parameter is varied the model undergoes
a transition between two oscillatory waveforms; a corresponding transition is
observed experimentally. After establishing the periodicity of the subcritical
oscillatory solution, the nature of the transition is studied. It is found to
be a resonance bifurcation, with the solution branching at the critical point
to another periodic solution of the same period. Using this result a
comparison is made between the model and experimental observations. The model
is found to predict and allow an interpretation of these observations.

Also, look at <http://www.scholarpedia.org/article/Plant_model>

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


