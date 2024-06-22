
# COVID-19 Analysis

## Project Overview
This project aims to analyze and predict the risk level of COVID-19 patients based on their current symptoms, status, and medical history. Using machine learning techniques, the goal is to assist healthcare providers in efficiently allocating medical resources and improving patient care during the pandemic.

## Dataset
The dataset used for this analysis was sourced from the [COVID-19 dataset on Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data). It contains anonymized information about COVID-19 patients, including their demographics, pre-existing conditions, symptoms, and outcomes.

### Dataset Details
- **Source**: [Kaggle COVID-19 Dataset](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data)
- **Number of Records**: 1,048,576 unique patients
- **Number of Features**: 21 unique features

### Features
- `sex`: 1 for female and 2 for male.
- `age`: Age of the patient.
- `classification`: COVID test findings. Values 1-3 indicate a COVID diagnosis, while 4 or higher means the patient is not a carrier or the test is inconclusive.
- `patient type`: Type of care received. 1 for returned home and 2 for hospitalization.
- `pneumonia`: Whether the patient has air sacs inflammation (1 for yes, 2 for no).
- `pregnancy`: Whether the patient is pregnant (1 for yes, 2 for no).
- `diabetes`: Whether the patient has diabetes (1 for yes, 2 for no).
- `copd`: Whether the patient has Chronic Obstructive Pulmonary Disease (1 for yes, 2 for no).
- `asthma`: Whether the patient has asthma (1 for yes, 2 for no).
- `inmsupr`: Whether the patient is immunosuppressed (1 for yes, 2 for no).
- `hypertension`: Whether the patient has hypertension (1 for yes, 2 for no).
- `cardiovascular`: Whether the patient has heart or blood vessel-related disease (1 for yes, 2 for no).
- `renal chronic`: Whether the patient has chronic renal disease (1 for yes, 2 for no).
- `other disease`: Whether the patient has another disease (1 for yes, 2 for no).
- `obesity`: Whether the patient is obese (1 for yes, 2 for no).
- `tobacco`: Whether the patient uses tobacco (1 for yes, 2 for no).
- `usmr`: Indicates treatment in medical units of different levels.
- `medical unit`: Type of institution that provided care.
- `intubed`: Whether the patient was connected to a ventilator (1 for yes, 2 for no).
- `icu`: Whether the patient was admitted to an Intensive Care Unit (1 for yes, 2 for no).
- `date died`: Date of death if the patient died, and '9999-99-99' otherwise.

## Usage
-Download the dataset from Kaggle and place it in the data/ directory.
-Run the Jupyter notebooks in the notebooks/ directory to perform data analysis, visualization, and model training.
-Evaluate the models and use the best-performing model for predictions.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
-The dataset was provided by the Mexican government and made available on Kaggle by Meir Nizri.
-Thanks to all the healthcare providers and researchers working tirelessly during the COVID-19 pandemic.
