
# CardioViscularStudy
This a Maven project that uses apache Spark and Hadoop for Coronary Heart Disease Prediction

## Technologies used:
- Apache Spark for Big Data management and machine learning models
- Hadoop (HDFS) for data storing
- Docker for running the project on a cluster
- jupyter NoteBook for data visualization 

  

## Project Steps:
- setting up a maven project and add apache Spark configuration
- loading , understanding and preprocessing data 
- explorotary data analyses using a jupyter notebook
- models creation and evaluation
- saving prediction results


## About dataset:

The dataset used  is publically available on the Kaggle website :  https://www.kaggle.com/datasets/christofel04/cardiovascular-study-dataset-predict-heart-disea , and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.
Variables
Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

### Data Description

#### Demographic:
-Sex: male or female("M" or "F")
- Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
#### Behavioral
- is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
#### Medical( history)
- BP Meds: whether or not the patient was on blood pressure medication (Nominal)
- Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
- Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
- Diabetes: whether or not the patient had diabetes (Nominal)
#### Medical(current)
- Tot Chol: total cholesterol level (Continuous)
- Sys BP: systolic blood pressure (Continuous)
- Dia BP: diastolic blood pressure (Continuous)
- BMI: Body Mass Index (Continuous)
- Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
- Glucose: glucose level (Continuous)
#### Predict variable (desired target)
- 10 year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)
