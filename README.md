# MODEL7434234848: APS

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL7434234848.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL7434234848.git@20140916`

## Usage

Importing the model package.

`import MODEL7434234848 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the flux balance model from:  
**A fragile metabolic network adapted for cooperation in the symbiotic bacterium Buchnera aphidicola.**   
Thomas GH, Zucker J, Macdonald SJ, Sorokin A, Goryanin I, Douglas AE.: _BMC
Syst Biol._ 2009 _Feb_ 21;3(1):24. pubmedID:
[19232131](http://www.ncbi.nlm.nih.gov/pubmed/19232131) , doi:
[10.1186/1752-0509-3-24](http://dx.doi.org/10.1186/1752-0509-3-24)

**Abstract:**   
**Background:** In silico analyses provide valuable insight into the biology of obligately intracellular pathogens and symbionts with small genomes. There is a particular opportunity to apply systems level tools developed for the model bacterium Escherichia coli to study the evolution and function of symbiotic bacteria which are metabolically specialised to overproduce specific nutrients for their host and, remarkably, have a gene complement that is asubset ofthe E. coli genome.   
**Results:** We have reconstructed and analysed the metabolic network of the gamma-proteobacterium Buchnera aphidicola (symbiont of the pea aphid) as a model for using systems-level approaches to discover key traits of symbionts with small genomes. The metabolic network is extremely fragile with >90 % of thereactions essential for viability in silico; and it is structured so that the bacterium cannot grow without producing the essential amino acid, histidine, which is released to the insect host. Further, the amount of essential amino acid produced by the bacterium in silico can be controlledby host supply of carbon and nitrogen substrates.   
**Conclusions:** This systems-level analysis predicts that the fragility of the bacterial metabolic network renders the symbiotic bacterium intolerant of drastic environmental fluctuations, while the coupling of histidine production to growth prevents the bacterium from exploiting host nutrients without reciprocating. These metabolic traits underpin the sustained nutritional contribution of B. aphidicola to the host and, together with the impact of host-derived substrates on the profile of nutrients released from the bacteria, point to a dominant role of the host in controlling the symbiosis. Systems level analysis of other taxa will establish the generality of these traits among symbiotic bacteria with reduced genomes. 

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


