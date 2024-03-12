# About ScoobyTables-pretrained

This repo contains pretrained models for [ScoobyTables](https://github.com/aalesv/ScoobyTables) software.

## Files description

### 2024_0312-knn-sh72531.dmp

Dataset is the same as 2024_0301-knn-sh72531.dmp. Table names changed to improve readability:

* Tipin to Tip_In
* Transignretard to Trans_Ign_Retard

This is k-nearest neighbors algorithm trained on following SH72531 CPU-based Subaru ROMs:

* EA1W310e
* EB4J321R
* EB4K010V
* EB4P000T
* EB4P000T

#### Algorithm parameters:

Numbers of neighbors = 2

#### Software versions:

Python version 3.11, pandas version 2.2.0, ScoobyTables version 2024.0301
