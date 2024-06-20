# AnDePeD

Accompanying repository for our paper on real-time anomaly detection on periodic
server farm telemetry data. We introduce our new algorithms; AnDePeD and AnDePeD Pro.

## Code
This folder contains the following implementations:
- a
- a
- b

## Data
This folder contains 


## Results
This folder contains the results shown in the paper as figures. 

- `anomaly_detection_performance_results.csv`: average results of six detectors from 
[NAB](https://github.com/numenta/NAB), AnDePeD and AnDePeD Pro (latter two in both online
operational modes: Mode-I and Mode-II), using the metrics of
Precision, Recall, F-score and MCC on the datasets in the **Data** folder\
(higher values are better, value range is $[0,1]$)

- `initialisation_delays.csv`: results of our initialisation delay calculations for
six detectors from [NAB](https://github.com/numenta/NAB), AnDePeD and AnDePeD Pro,
based on their respective publications or implementations\
(lower values are better, value range is $[0, \infty]$ in theory and $[0, 4621]$ in practice)

- `detection_delay_results_Mode-I.csv`: average results of detection delays by six detectors
from [NAB](https://github.com/numenta/NAB), AnDePeD and AnDePeD Pro (latter two in Mode-I)\
(lower values are better, value range is $[0, \infty]$ in theory and $[0, 4621]$ in practice)