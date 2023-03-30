# README for data used in the prediction of boiling and melting points of organic compounds using the UPPER approach by Dr. Samuel Yalkowsky and his lab

## Overview 
Data used for manuscript: One boiling and one melting database in .xlsx format created using peer-reviewed papers, NIST, and PUBCHEM.

***

## Purpose of the study 
### To create models that predict physical properties of organic compounds based on structure. 


## Structure of the data
Note: Column nomenclature is as follows:
CAS (Chemical Abstracts Service), dhm at Tm (enthalpy of melting at the melting point), 
Tm (melting point), 
dhv at Tb (enthalpy of boiling at the boiling point), 
Tb (boiling point), 
SD (standard deviation), 
smile/smiles (simplified molecular-input line-entry system), 
Formula is chemical formula if available (will omit since it is unnecessary for the code to work).

#### Meltingdatabase.xlsx
###### Meltingdatabase
* Column1: CAS (Chemical Abstracts Service) number is a unique and unambiguous identifier for a specific compound.
* Column2: Name of compound
* Column3: Array of enthalpy values used for average and standard deviation
* Column4: Array of melting point values used for average and standard deviation
* Column5: Average of values from column 3
* Column6: Median of enthapy from column 3
* Column7: Standard deviation of values from column 3
* Column8: Average of values from column 4
* Column9: Median of values from column 4
* Column10: Standard deviation of values from column 4
* Column11: smile of compound 
* Column12: References of enthalpy data in the order corresponding to the array of values in column 3
* Column13: References of melting point data in the order corresponding to the array of values in column 4


#### boilingdatabase.xlsx
###### boilingdatabase
* Column1: CAS (Chemical Abstracts Service) number is a unique and unambiguous identifier for a specific compound.
* Column2: Name of compound
* Column3: Array of enthalpy values used for average and standard deviation
* Column4: Array of boiling point values used for average and standard deviation
* Column5: Average of values from column 3
* Column6: Median of enthapy from column 3
* Column7: Standard deviation of values from column 3
* Column8: Average of values from column 4
* Column9: Median of values from column 4
* Column10: Standard deviation of values from column 4
* Column11: smile of compound 
* Column12: References of enthalpy data in the order corresponding to the array of values in column 3
* Column13: References of boiling point data in the order corresponding to the array of values in column 4
***
