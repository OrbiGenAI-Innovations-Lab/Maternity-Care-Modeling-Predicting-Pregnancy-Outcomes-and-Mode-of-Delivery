# Data Collection 

- Dataset collection and gathering -> dataset including historical pregnancy and childbirth data with relevant features such as maternal health records, prenatal test results, demographic information, and ultrasound data, etc..
- Labeling data -> annotate the dataset with labels
- Data Quality Check

## Data Pre-Processing

- feature engineering
- data splitting
- normalization/scaling


### Dataset Resources 

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



## Dataset Used For our Study



- Approx. date of delivery
  - [Ultrasound Image Data](https://zenodo.org/record/3904280)
  - [Mother's Age, Weight, Height, weather she smokes, gestation length](https://www.kaggle.com/datasets/debjeetdas/babies-birth-weight)
  - [Maternal Mortality ratio from every country ](https://data.worldbank.org/indicator/SH.STA.MMRT?end=2017&start=2000&view=chart)
  - [Other health parameters (e.g., blood pressure, blood glucose levels)](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)
  - [Complicatios Arised during Pregnancy(India)](https://data.gov.in/files/ogdpv2dms/s3fs-public/Percentage_Women_complication_Pregnancy_delivery_post-delivery_vaginal_discharge_menstrual_DLHS4.csv)
  - [Race/ Ethnicity](https://data.cityofnewyork.us/Health/Pregnancy-Associated-Mortality/27x4-cbi6/explore/query/SELECT%0A%20%20%60year%60%2C%0A%20%20%60related%60%2C%0A%20%20%60underlying_cause%60%2C%0A%20%20%60race_ethnicity%60%2C%0A%20%20%60borough%60%2C%0A%20%20%60deaths%60/page/filter)
  - [Complications](https://data.cityofnewyork.us/Health/Pregnancy-Risk-Assessment-Monitoring-System-PRAMS-/rqgf-94xs/explore/query/SELECT%0A%20%20%60year%60%2C%0A%20%20%60source%60%2C%0A%20%20%60question%60%2C%0A%20%20%60prevalence%60%2C%0A%20%20%60lower_95_confidence_interval%60%2C%0A%20%20%60upper_95_confidence_interval%60%0AORDER%20BY%20%60year%60%20DESC%20NULL%20FIRST/page/filter)
  - [Parental Care History](https://wonder.cdc.gov/wonder/help/lbd-expanded.html#)
  - [child health and other medical history](https://www.kaggle.com/datasets/gauravduttakiit/reproductive-childhealthcare-classification)
- Preeclampsia
  - Dataset for this has already been prepared by us.
  - [Link](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
  - [Link](https://www.kaggle.com/datasets/debjeetdas/babies-birth-weight)
  - [Link](https://wonder.cdc.gov/wonder/help/lbd-expanded.html#)
  - 
- Childbirth weight
  - [Ultrasound Image Data](https://zenodo.org/record/3904280)
  - [Mother's Age, Weight, Height, weather she smokes, gestation length](https://www.kaggle.com/datasets/debjeetdas/babies-birth-weight)
  - [Maternal Mortality ratio from every country ](https://data.worldbank.org/indicator/SH.STA.MMRT?end=2017&start=2000&view=chart)
  - [Other health parameters (e.g., blood pressure, blood glucose levels)](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)
  - [Complicatios Arised during Pregnancy(India)](https://data.gov.in/files/ogdpv2dms/s3fs-public/Percentage_Women_complication_Pregnancy_delivery_post-delivery_vaginal_discharge_menstrual_DLHS4.csv)
  - [Race/ Ethnicity](https://data.cityofnewyork.us/Health/Pregnancy-Associated-Mortality/27x4-cbi6/explore/query/SELECT%0A%20%20%60year%60%2C%0A%20%20%60related%60%2C%0A%20%20%60underlying_cause%60%2C%0A%20%20%60race_ethnicity%60%2C%0A%20%20%60borough%60%2C%0A%20%20%60deaths%60/page/filter)
  - [Complications](https://data.cityofnewyork.us/Health/Pregnancy-Risk-Assessment-Monitoring-System-PRAMS-/rqgf-94xs/explore/query/SELECT%0A%20%20%60year%60%2C%0A%20%20%60source%60%2C%0A%20%20%60question%60%2C%0A%20%20%60prevalence%60%2C%0A%20%20%60lower_95_confidence_interval%60%2C%0A%20%20%60upper_95_confidence_interval%60%0AORDER%20BY%20%60year%60%20DESC%20NULL%20FIRST/page/filter)
  - [Parental Care History](https://wonder.cdc.gov/wonder/help/lbd-expanded.html#)
  - [child health and other medical history](https://www.kaggle.com/datasets/gauravduttakiit/reproductive-childhealthcare-classification)
- Mode of Delivery
  - [Link](https://www.kaggle.com/datasets/gauravduttakiit/reproductive-childhealthcare-classification)
  - [Ultrasound Image Data(fetal position, etc)](https://zenodo.org/record/3904280)
  - [Mother's Age, Weight, Height, weather she smokes, gestation length](https://www.kaggle.com/datasets/debjeetdas/babies-birth-weight)
  - [Other health parameters (e.g., blood pressure, blood glucose levels)](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)
  - [pelvic measurments](https://www.kaggle.com/datasets/gauravduttakiit/reproductive-childhealthcare-classification))
  - [Complicatios Arised during Pregnancy(India)](https://data.gov.in/files/ogdpv2dms/s3fs-public/Percentage_Women_complication_Pregnancy_delivery_post-delivery_vaginal_discharge_menstrual_DLHS4.csv)
  - [Complications](https://data.cityofnewyork.us/Health/Pregnancy-Risk-Assessment-Monitoring-System-PRAMS-/rqgf-94xs/explore/query/SELECT%0A%20%20%60year%60%2C%0A%20%20%60source%60%2C%0A%20%20%60question%60%2C%0A%20%20%60prevalence%60%2C%0A%20%20%60lower_95_confidence_interval%60%2C%0A%20%20%60upper_95_confidence_interval%60%0AORDER%20BY%20%60year%60%20DESC%20NULL%20FIRST/page/filter)
- Pregnancy Outcomes
