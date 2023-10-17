## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Dataset](#dataset)
- [Data pre-processing]()
- [Installation](#installation)
- [Usage]()
- [Models]()
- [Results](#results)
- [Model Interpretation]()
- [Ethical Considerations]()
- [Acknowledgements]()

## Introduction

Maternity Care Modeling is an interdisciplinary field that combines healthcare, data science, and artificial intelligence to enhance the understanding and prediction of various aspects of pregnancy and childbirth. This includes predicting pregnancy outcomes, such as complications or the likelihood of a successful pregnancy, as well as predicting the mode of delivery, whether it's vaginal or through a cesarean section (C-section).

### Significance

Pregnancy and childbirth are among the most transformative and crucial experiences in an individual's life. Maternity care plays a pivotal role in ensuring the well-being of both the expectant parent and the unborn child. By leveraging advanced data analysis and predictive modeling, we can:

- Improve Healthcare Decision-Making: Healthcare professionals can benefit from accurate predictions to make informed decisions about prenatal care, interventions, and delivery methods.
- Enhance Patient Care: Pregnant individuals can receive personalized care plans based on their unique risks and characteristics, leading to improved health outcomes and reduced maternal and neonatal mortality rates.
- Resource Allocation: Hospitals and healthcare systems can allocate resources more efficiently by identifying high-risk pregnancies in advance, reducing the burden on overtaxed healthcare facilities.


## Objective

The main objectives of this project are as follows:

- Predict pregnancy outcomes (e.g., complications) using machine learning and deep learning techniques.
- Predict the mode of delivery (vaginal or cesarean section) for pregnant patients.
- Predicting the Approx. date of delivery
- Predicting the childbirth weight
- Predicting preeclampsia

We believe that Maternity Care Modeling has the potential to make a significant positive impact on the lives of expectant parents and their children.


## Dataset

Data Description including information such as the data source, size, and a brief overview of the features. 

| Dataset/Resource Description                                      | URL                                                                                                   |
|------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| Babies Birth Weight Dataset (Kaggle)                              | [Link](https://www.kaggle.com/datasets/debjeetdas/babies-birth-weight)                                |
| Fetal Health Classification Dataset (Kaggle)                      | [Link](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)                            |
| UNICEF Country Data for India                                     | [Link](https://data.unicef.org/country/ind/)                                                           |
| UNICEF Global Data Explorer for India                              | [Link](https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=IND.CME_TMY0T4.&startPeriod=1970&endPeriod=2023) |
| World Bank Maternal Mortality Rate Indicator                       | [Link](https://data.worldbank.org/indicator/SH.STA.MMRT?end=2017&start=2000&view=chart)              |
| Maternal Health Risk Data (Kaggle)                                | [Link](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)                                |
| Our World in Data - Maternal Mortality                            | [Link](https://ourworldindata.org/maternal-mortality)                                                |
| Percentage Women Complication Pregnancy/Delivery Data (India)      | [Link](https://data.gov.in/files/ogdpv2dms/s3fs-public/Percentage_Women_complication_Pregnancy_delivery_post-delivery_vaginal_discharge_menstrual_DLHS4.csv) |
| Pregnancy-Associated Mortality Data (New York City)                | [Link](https://data.cityofnewyork.us/Health/Pregnancy-Associated-Mortality/27x4-cbi6/explore/query/SELECT%0A%20%20%60year%60%2C%0A%20%20%60related%60%2C%0A%20%20%60underlying_cause%60%2C%0A%20%20%60race_ethnicity%60%2C%0A%20%20%60borough%60%2C%0A%20%20%60deaths%60/page/filter) |
| CDC Wonder - Pregnancy Data (United States)                       | [Link](https://wonder.cdc.gov/controller/datarequest/D159)                                          |
| Reproductive Child Healthcare Classification Dataset (Kaggle)     | [Link](https://www.kaggle.com/datasets/gauravduttakiit/reproductive-childhealthcare-classification) |
| UNICEF Healthy Mothers, Healthy Babies Resource                    | [Link](https://data.unicef.org/resources/healthy-mothers-healthy-babies/)                             |
| Smoking During Pregnancy Statistics (England)                     | [Link](https://www.statista.com/statistics/445149/smoking-during-pregnant-in-england/)                 |
| Zenodo - Reproductive Healthcare Data                             | [Link](https://zenodo.org/record/3904280)                                                             |


## Data Preprocessing

- Feature Engineering: Identifying the relevant features and extracting relevant features from the dataset that might contribute to better predictions.
- Data Splitting: Splitting the dataset into training, validation, and test sets is crucial for evaluating the model's performance.
- Normalization/Scaling: Normalizing and scaling the numerical features to ensure that they have the same range.


## Models Selection and Architecture

List and briefly describe the machine learning and deep learning models you used in your project. Include any special considerations or hyperparameters.

- Logistic Regression/Random Forest/SVM
- Regression Models 
- Neural Networks (CNN or RNN)
- Predictive Modeling

## Model Workflow




  
<!---
*Model Architecture:*

The architecture of the model including the number of layers, activation functions, etc..
--->

## Model Training 

- Training separate models for each prediction task :
  - pregnancy outcomes
  - mode of delivery
  - approx. date of delivery
  - preeclampsia
  - childbirth weight

*Optimizing the hyperparameters using the validation set*

- Ensemble Methods
  - Stacking
  - Bagging

*Used to combine predictions from multiple models for improved accuracy*

## Installation

Instructions on how to set up the project locally. Including any dependencies or libraries that need to be installed. 

```bash
pip install -r requirements.txt
```

## Results 

- Evaluation Metrics Performance
  - Accuracy, Precision, Recall, F1-score, MAE, MSE 
- Interpretability 
  - SHAP values, feature importance scores, and gradient-based methods to interpret model predictions, especially for healthcare applications where interpretability is crucial.


## Model Interpretation
<!---
## Deployment




## Contributors

We would like to thank the following contributors for their valuable contributions to this project:
--> 
## Ethical Considerations






## Acknowledgements


<p align="center">
Made with :heart: by OrbiGenAI Innovations Lab <br>
Copyright | @orbigenai All Rights Reserved
</p>


