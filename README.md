Python scripts and data of the paper: **"A Data-Driven Framework for Predicting PHBV Biodegradation-Induced Weight Loss Based on Laboratory and Real-Environment Condition Tests"** by Marianna I Kotzabasaki, Leonidas Mindrinos, Nikolaos P Sotiropoulos, Konstantina V Filippou and Chrysanthos Maraveas, published in Polymers 18(7), 897 (2026). https://www.mdpi.com/2073-4360/18/7/897

This repository contains the machine learning workflow developed for predicting weight or mass loss percentage of PHBV polymers.

This folder includes:

1) Original dataset (*_raw_LM.xlsx)

2) Preprocessing notebook (*_data_preprocessing_LM.ipynb)

3) Cleaned dataset (*_data_LM.csv) Dataset obtained after preprocessing (cleaning, filtering, unit harmonization, removing invalid samples).

4) Final training and deployment on Jaqpot notebook (*_regression_LM.ipynb)

The deployed model on Jaqpot (https://app.jaqpot.org/dashboard/models/2343/description) was trained and optimized using Random Forest–based techniques tailored to the available experimental data.

**Acknowledgments**

This work is based on research conducted within the framework of the Horizon Europe European Commission project ANIPH (Grant Agreement No. 101181943). The content of the paper is the sole responsibility of its authors and does not necessarily reflect the views of the European Commission.
