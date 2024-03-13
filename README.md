# About ScoobyTables-pretrained

This repo contains pretrained models for [ScoobyTables](https://github.com/aalesv/ScoobyTables) software.

## Files description

### 2024_0313-knn-sh72531.dmp

Dataset is the same as 2024_0301-knn-sh72531.dmp. Table names changed to improve prediction:

* Timing_Idle_Above_A_RPM to Timing_Idle_Above_RPM
* Timing_Idle_Above_B_RPM to Timing_Idle_Above_RPM
* Timing_Idle_Above_A_ECT to Timing_Idle_Above_ECT
* Timing_Idle_Above_B_ECT to Timing_Idle_Above_ECT

This is k-nearest neighbors algorithm trained on following SH72531 CPU-based Subaru ROMs:

* EA1W310e
* EB4J321R
* EB4K010V
* EB4P000T
* EB4P000T

#### Algorithm parameters:

Numbers of neighbors = 2

#### Software versions:

Python version 3.11, scikit-learn version 1.4.1.post1, ScoobyTables version 2024.0311
