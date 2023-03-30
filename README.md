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
    ├── data/               # database created by the author using peer-reviewed manuscripts, PUBCHEM, and NIST
    │           
    |   
    └── supplementary-materials/
        ├── Supplementary_Figures/     
        |                   # supplementary figures for the main manuscript
        └── Supplementary_Tables/      
                            # supplementary tables for the main manuscript 
    
    Python                           # scripts to run in the following order (also see associated README.md)
        └── Batchfragmenter.py       # PYTHON code in JUPYTER Notebooks used to create molecular fragments of compounds based on figure 1 in Supplementary_Figures


