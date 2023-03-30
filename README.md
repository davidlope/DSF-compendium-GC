# Project Description
Code and data associated with future manuscript on the prediction of boiling and melting points of organic compounds using the UPPER approach by Dr. Samuel Yalkowsky and his lab

UPPER description: https://pubmed.ncbi.nlm.nih.gov/24909850/

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## File Organization

    analysis/
    |
    ├── logs/
    │   └── log.md          # learning log for DSF
    |
    ├── figures/            # location of the figures produced for the manuscript
    |
    ├── data/               # melting and boiling databases created by the author using peer-reviewed manuscripts, PUBCHEM, and NIST
    │           
    |   
    └── supplementary-materials/
        ├── Supplementary_Figures/     
        |                   # supplementary figures for the main manuscript
        └── Supplementary_Tables/      
                            # supplementary tables for the main manuscript 
    
    Python                           # scripts to run in the following order (also see associated README.md)
        └── Batchfragmenter.ipynb    # PYTHON code in JUPYTER Notebooks used to create molecular fragments of compounds based on figure 1 in figures

## Prerequisites
At least Python 3.6 or access to Google Colab/ Jupyter Notebooks.
To install RDKit, you can find installation instructions below.
## Installation
In JUPYTER Notebooks use the following line to install RDKIT:
!pip install pandas rdkit_pypi

In JUPYTER Notebooks run the following lines:
import pandas as pd
from io import StringIO
from rdkit import Chem
from collections import Counter
from rdkit.Chem import rdMolDescriptors, Descriptors3D, AllChem
from rdkit.Chem.Descriptors import MolWt
import numpy as np 

# Acknowledgements
The author is grateful for DAYLIGHT SMILES resources to create the SMARTS fingerprints for fragmentation. This work wouldn't be possible without the work of the RDKit team, as well as Cédric Bouysset and his work on mols2grid. Thanks!
