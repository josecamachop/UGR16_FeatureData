
# UGR16 Feature data 

This repository contains the four feature data variants of UGR'16 used in the following papers:

- Camacho, Wasielewska, Espinosa, Fuentes-García. Quality In / Quality Out: Data quality more relevant than model choice in anomaly detection with the UGR’16. IEEE/IFIP Network Operations and Management Symposium. Miami, USA. 2023. 

- Camacho, Wasielewska, Fuentes-García, Rodríguez-Gómez. Quality In / Quality Out: Assessing Data Quality in an Anomaly Detection Benchmark. arXiv preprint arXiv:... [stat.ML]

Please, make sure to reference the last paper when using the data.

Data is provided in Malab format, csv format and excel format.

The original UGR'16 can be downloaded from https://nesg.ugr.es/nesg-ugr16/index.php

A new version with updated nfcapd format can be found at https://codas.ugr.es/animalicos/en/results#datasets

Contact person: José Camacho (josecamacho@ugr.es)

Last modification of this document: 26/May/23


## Repository organization

The folder is organized as follows:

- folder csv: Contains the feature data in csv format.

- folder excel: Contains the feature data in excelformat.

- folder matlab: Contains the feature data in Matlab format.

Each of the datasets contains the training data (X-train), the training labelling (Y-train), the test data (X-test) and the test labelling (Y-test).


## Variants description following the Matlab data
 
- UGR16v1

 train:

 X: [134262 x 134] feature data
 Y: [134262 x 8] counts of attacks per observation
 obs_l: [134262 x 1] observation label (timestamp)
 var_l: [1 x 134] feature label
 yvar_l: [1 x 8] attack label
 classM: [134262 x 1] minute in the day
 classD: [134262 x 1] day timestamp
 classWD: [134262 x 1] workday (1) vs weekend (2)

 test:

 test: [43200 x 134] feature data
 Yt: [43200 x 8] counts of attacks per observation
 obs_lt: [43200 x 1] observation label (timestamp)
 classMt: [43200 x 1] minute in the day
 classDt: [43200 x 1] day timestamp
 classWDt: [43200 x 1] workday (1) vs weekend (2)
 
- UGR16v2

 train:

 X: [98262 x 134] feature data
 Y: [98262 x 8] counts of attacks per observation
 obs_l: [98262 x 1] observation label (timestamp)
 var_l: [1 x 134] feature label
 yvar_l: [1 x 8]attack label
 classM: [98262 x 1] minute in the day
 classD: [98262 x 1] day timestamp
 classWD: [98262 x 1] workday (1) vs weekend (2)

 test:

 test: [43200 x 134] feature data
 Yt: [43200 x 8] counts of attacks per observation
 obs_lt: [43200 x 1] observation label (timestamp)
 classMt: [43200 x 1] minute in the day
 classDt: [43200 x 1] day timestamp
 classWDt: [43200 x 1] workday (1) vs weekend (2)

- UGR16v2NoIRC

 train:

 X: [98262 x 132] feature data
 Y: [98262 x 8] counts of attacks per observation
 obs_l: [98262 x 1] observation label (timestamp)
 var_l: [1 x 132] feature label
 yvar_l: [1 x 8]attack label
 classM: [98262 x 1] minute in the day
 classD: [98262 x 1] day timestamp
 classWD: [98262 x 1] workday (1) vs weekend (2)

 test:

 test: [43200 x 132] feature data
 Yt: [43200 x 8] counts of attacks per observation
 obs_lt: [43200 x 1] observation label (timestamp)
 classMt: [43200 x 1] minute in the day
 classDt: [43200 x 1] day timestamp
 classWDt: [43200 x 1] workday (1) vs weekend (2)

- UGR16v3

 train:

 X: [72644 x 134] feature data
 Y: [72644 x 8] counts of attacks per observation
 obs_l: [72644 x 1] observation label (timestamp)
 var_l: [1 x 134] feature label
 yvar_l: [1 x 8] attack label
 classM: [72644 x 1] minute in the day
 classD: [72644 x 1] day timestamp
 classWD: [72644 x 1] workday (1) vs weekend (2)

 test:

 test: [43200 x 134] feature data
 Yt: [43200 x 8] counts of attacks per observation
 obs_lt: [43200 x 1] observation label (timestamp)
 classMt: [43200 x 1] minute in the day
 classDt: [43200 x 1] day timestamp
 classWDt: [43200 x 1] workday (1) vs weekend (2)

- UGR16v4

 train:

 X: [72644 x 134] feature data
 Y: [72644 x 8] counts of attacks per observation
 obs_l: [72644 x 1] observation label (timestamp)
 var_l: [1 x 134] feature label
 yvar_l: [1 x 8] attack label
 classM: [72644 x 1] minute in the day
 classD: [72644 x 1] day timestamp
 classWD: [72644 x 1] workday (1) vs weekend (2)

 test:

 test: [43200 x 134] feature data
 Yt: [43200 x 8] counts of attacks per observation
 obs_lt: [43200 x 1] observation label (timestamp)
 classMt: [43200 x 1] minute in the day
 classDt: [43200 x 1] day timestamp
 classWDt: [43200 x 1] workday (1) vs weekend (2)

- UGR16v3v4

 train:

 X: [72644 x 268] feature data
 Y: [72644 x 8] counts of attacks per observation
 obs_l: [72644 x 1] observation label (timestamp)
 var_l: [1 x 268] feature label
 yvar_l: [1 x 8] attack label
 classM: [72644 x 1] minute in the day
 classD: [72644 x 1] day timestamp
 classWD: [72644 x 1] workday (1) vs weekend (2)

 test:

 test: [43200 x 268] feature data
 Yt: [43200 x 8] counts of attacks per observation
 obs_lt: [43200 x 1] observation label (timestamp)
 classMt: [43200 x 1] minute in the day
 classDt: [43200 x 1] day timestamp
 classWDt: [43200 x 1] workday (1) vs weekend (2)

