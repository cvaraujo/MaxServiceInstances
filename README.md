# Max Service Under Quality of Service Constraints - Instances
The first set of instances to the Max Service Problem

## Getting Started

This set of instances was made from a washington map slice extracted from OpenStreeMaps with area of 50 x 50, 75 x 75 and 100 x 100

### QoS Metrics
For this instances, the QoS metrics calculated was:
* Delay
* Delay Variation between paths
* Jitter
* Bandwidth
* Link Duration Estimation

### Folders
This first benchmark set contains 39 instances divided em 3 folders, each folder is represented in following pattern: City-SizeOfMap. Inside each of this folders has 10 subfolders ranging from 10 to 100, just to organization of the instances.

### Instance Format
Each instance is composed for two files o "washington-SizeOfMap-NumberOfNodes-NumberOfTerminals.txt", that contains the network topology along with the QoS metrics, and the "param-washington-SizeOfMap-NumberOfNodes-NumberOfTerminals.txt" containing the threshold of each metric for this instance.

### Param
the parameter archive was calculated based on the graph. Will be called "Degree of Freedom", from any metric, how close this metric was to the maximum value needed to solve the model itself, without the set of restrictions becoming a relevant difficulty factor. The degree of freedom for each metric is on scale 0 < degree <= 1. The degrees used was: 
* Delay: 0.7
* Jitter: 0.8
* Delay variation: 0.8


