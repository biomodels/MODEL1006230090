# MODEL1006230090: Wu2007_MitochondrialTCAcycle

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230090.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230090.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230090 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Computer modeling of mitochondrial tricarboxylic acid cycle, oxidative phosphorylation, metabolite transport, and electrophysiology.**   
Wu F, Yang F, Vinnakota KC, Beard DA. _J Biol Chem_ 2007 Aug
24;282(34):24525-37 [17591785](http://www.ncbi.nlm.nih.gov/pubmed/17591785) ,  
**Abstract:**   
A computational model of mitochondrial metabolism and electrophysiology is
introduced and applied to analysis of data from isolated cardiac mitochondria
and data on phosphate metabolites in striated muscle in vivo. This model is
constructed based on detailed kinetics and thermodynamically balanced reaction
mechanisms and a strict accounting of rapidly equilibrating biochemical
species. Since building such a model requires introducing a large number of
adjustable kinetic parameters, a correspondingly large amount of independent
data from isolated mitochondria respiring on different substrates and subject
to a variety of protocols is used to parameterize the model and ensure that it
is challenged by a wide range of data corresponding to diverse conditions. The
developed model is further validated by both in vitro data on isolated cardiac
mitochondria and in vivo experimental measurements on human skeletal muscle.
The validated model is used to predict the roles of NAD and ADP in regulating
the tricarboxylic acid cycle dehydrogenase fluxes, demonstrating that NAD is
the more important regulator. Further model predictions reveal that a decrease
of cytosolic pH value results in decreases in mitochondrial membrane potential
and a corresponding drop in the ability of the mitochondria to synthesize ATP
at the hydrolysis potential required for cellular function.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Wu F, Yang F, Vinnakota KC, Beard DA. (2007) -
version=1.0**
](http://models.cellml.org/exposure/6fd3e797487ccf874a6f9068cd4d2295)  
The original CellML model was created by:  
**Geoffrey Nunns**   
gnunns1@jhu.edu  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


