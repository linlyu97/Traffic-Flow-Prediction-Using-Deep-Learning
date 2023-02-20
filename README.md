# Traffic-Flow-Prediction-Using-Deep-Learning

### Understand the Data
#### Data Introduction
The data is from the Caltrans Performance Measurement System (PeMS) database, http://pems.dot.ca.gov/. The traffic data are collected every 5 min from over 15000 individual detectors, which are deployed statewide in freeway systems across California.

#### Data Preprocessing

The collected data are aggregated 5-min interval each for each detector station. I plan to use the traffic flow data in the weekdays of the July, August, September of the year 2020 for the experiments.

July and August data as the training set, and September data as the testing set.

For freeways with multiple detectors, the traffic data collected by different detectors are aggregated to get the average traffic flow of this freeway.


Data source:
```
Armstrong County HW 2 File.csv
```
For more code details:
```
Traffic Flow Prediction.ipynb
```
