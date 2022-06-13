## DATA ASSIGNMENT

Dataset: COVID-19 Diagnostic Laboratory Testing (PCR Testing) Time Series 
Submitted by: Aakash Patel

#### 1.1 Introduction

Dataset of COVID-19’s Diagnostic Data is used for the purpose of Data Analytics and answering key business questions. Please run the Jupyter notebook (.ipynb) for more. Database keeps updating with new records. Please find it at here: [COVID-19 Diagnostic Laboratory Testing (PCR Testing) Time Series] (https://healthdata.gov/dataset/COVID-19-Diagnostic-Laboratory-Testing-PCR-Testing/j8mb-icvb)
The notebook automatically downloads and uses the dataset. 

#### 1.2 Dataset Description [1]

This time series dataset includes viral COVID-19 laboratory test [Polymerase chain reaction (PCR)] results from over 1,000 U.S. laboratories and testing locations including commercial and reference laboratories, public health laboratories, hospital laboratories, and other testing locations. Data are reported to state and jurisdictional health departments in accordance with applicable state or local law and in accordance with the Coronavirus Aid, Relief, and Economic Security (CARES) Act (CARES Act Section 18115).

**Note:**
Data are provisional and subject to change.

Data presented here is representative of diagnostic specimens being tested - not individual people - and excludes serology tests where possible. Data presented might not represent the most current counts for the most recent 3 days due to the time it takes to report testing information. The data may also not include results from all potential testing sites within the jurisdiction (e.g., non-laboratory or point of care test sites) and therefore reflect the majority, but not all, of COVID-19 testing being conducted in the United States.

Sources: CDC COVID-19 Electronic Laboratory Reporting (CELR), Commercial Laboratories, State Public Health Labs, In-House Hospital Labs

Data for each state is sourced from either data submitted directly by the state health department via COVID-19 electronic laboratory reporting (CELR), or a combination of commercial labs, public health labs, and in-house hospital labs. Data is taken from CELR for states that either submit line level data or submit aggregate counts which do not include serology tests.

#### 1.3 Steps to Run

1. Install Python 3.7 or above with pip
2. Install Jupyter notebook in machine using below command
	    `pip install notebook`
3. Open command prompt in the repo’s root directory.
4. Execute below command
        `jupyter notebook`
5. Find the notebook Assignment.ipynb file and run the cells one by one from top.

#### Metrics Description

Dataset is analysed on following metrics:
    1. The total number of PCR tests performed as of yesterday in the United States.
    2. The 7-day rolling average number of new cases per day for the last 30 days.
    3. The 10 states with the highest test positivity rate (positive tests / tests performed) for tests performed in the last 30 days.

**Note:** Metrics Results Description and Conclusions are provided in the notebook(.ipynb) in the root directory, at the end of metrics' respective code section. 

#### References

[1] Healthdata.gov, 2022. [Online]. Available: https://healthdata.gov/dataset/COVID-19-Diagnostic-Laboratory-Testing-PCR-Testing/j8mb-icvb. [Accessed: 13- Jun- 2022].
