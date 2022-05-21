# ECG_Classification

## DATASET
The original datasets used are https://www.physionet.org/physiobank/database/mitdb/ and https://www.physionet.org/physiobank/database/ptbdb/  
we are going to use an annotated dataset(https://www.kaggle.com/shayanfazeli/heartbeat) of heartbeats already preprocessed by the authors of this paper(https://arxiv.org/abs/1805.00794) to see if we can train a model to detect abnormal heartbeats.  

**MIT-BIH Arrhythmia dataset :**

Number of Categories: 5
Number of Samples: 109446
Sampling Frequency: 125Hz
Data Source: Physionet’s MIT-BIH Arrhythmia Dataset
Classes: [’N’: 0, ‘S’: 1, ‘V’: 2, ‘F’: 3, ‘Q’: 4]  

**The PTB Diagnostic ECG Database**

Number of Samples: 14552
Number of Categories: 2 ( Normal vs Abnomal)
Sampling Frequency: 125Hz
Data Source: Physionet’s PTB Diagnostic Database
