# Detecting Parkinson's Disease

This repository contains the code and resources for detecting Parkinson's disease using a machine learning model. The project utilizes a dataset of biomedical voice measurements to differentiate between healthy individuals and those with Parkinson's disease.

## Dataset

The dataset used in this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set). The dataset includes a range of voice measurements from 31 individuals, 23 of whom have Parkinson's disease. Each row in the dataset corresponds to one of 195 voice recordings.

### Dataset Information

- **Source:** Max Little, Patrick E. McSharry, Eric J. Hunter, Lorraine O. Ramig (2008)
- **Publication:** 'Suitability of dysphonia measurements for telemonitoring of Parkinson's disease', IEEE Transactions on Biomedical Engineering.

### Attribute Information

- `name` - ASCII subject name and recording number
- `MDVP:Fo(Hz)` - Average vocal fundamental frequency
- `MDVP:Fhi(Hz)` - Maximum vocal fundamental frequency
- `MDVP:Flo(Hz)` - Minimum vocal fundamental frequency
- `MDVP:Jitter(%)`, `MDVP:Jitter(Abs)`, `MDVP:RAP`, `MDVP:PPQ`, `Jitter:DDP` - Measures of variation in fundamental frequency
- `MDVP:Shimmer`, `MDVP:Shimmer(dB)`, `Shimmer:APQ3`, `Shimmer:APQ5`, `MDVP:APQ`, `Shimmer:DDA` - Measures of variation in amplitude
- `NHR`, `HNR` - Measures of the ratio of noise to tonal components in the voice
- `status` - Health status of the subject (0 - healthy, 1 - Parkinson's)
- `RPDE`, `D2` - Nonlinear dynamical complexity measures
- `DFA` - Signal fractal scaling exponent
- `spread1`, `spread2`, `PPE` - Nonlinear measures of fundamental frequency variation

