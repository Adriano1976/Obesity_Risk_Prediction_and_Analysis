# <font color=red><strong>Obesity Risk Prediction (Multi-Class)</strong></font>

Data for this competition (both training and testing) were generated from a deep learning model trained in the risk data set or cardiovascular disease.The characteristics distributions are close, but not exactly the same, those of the original data set.I feel free to use the original data set as part of this competition, both to explore differences and to see if incorporating the original in training improves model performance.

![image](https://github.com/Adriano1976/Obesity_Risk_Prediction_and_Analysis/assets/17755195/8d4feb4c-5357-4fb9-8fec-e16fe0e1bd70)

### Facts

- 📊 The data set was generated from a deep learning model trained in the risk data set or cardiovascular disease.
- 📑 Training and testing sets are available in order to predict the Nobeyesdad class for each line in the test assembly.
- 💡 This data set is especially suitable for views, groupings and data exploration in general.
- 🔄 Distributions of characteristics in the training and test data sets are close, but not exactly the same, those of the original data set.
- 📈 The use of the original data set is encouraged to investigate differences and evaluate if incorporating it into training improves model performance.

# Introduction
<div style="font-size:120%"> 
    <b>Goal:</b> We have to predict obesity risk in individuals.<br><br>
    <b>Dataset Description:</b>
</div>

| Column | Full Form | Description| 
|---|---|---|
| 'id'| id | Unique for each person(row)|
|'Gender'| Gender| person's Gender|
| 'Age' | Age| Dtype is float. Age is between 14 years to 61 years |
|'Height'| Height | Height is in meter it's between 1.45m to 1.98m|
| 'Weight' | Weight| Weight is between 39 to 165. I think it's in KG.|
|'family_history_with_overweight'| family history <br> with overweight| yes or no question|
| 'FAVC'| Frequent consumption <br> of high calorie food| it's yes or no question. i think question they asked is <br>do you consume high calorie food|
|'FCVC'|  Frequency of <br>consumption of vegetables| Similar to FAVC. this is also `yes or no` question|
|'NCP'| Number of main meals| dtype is float, NCP is between 1 & 4. I think it should be 1,2,3,4 <br>but our data is synthetic so it's taking float values|
|'CAEC'| Consumption of <br>food between meals| takes 4 values `Sometimes`, `Frequently`, `no` & `Always` <br>|
| 'SMOKE'| Smoke | yes or no question. i think the question is "Do you smoke?" |
|'CH2O'| Consumption of <br>water daily| CH2O takes values between 1 & 3. again it's given as <br>float may be because of synthetic data. it's values should be 1,2 or 3|
|'SCC'|  Calories consumption <br>monitoring| yes or no question|
|'FAF'| Physical activity <br>frequency| FAF is between 0 to 3, 0 means no physical activity<br> and 3 means high workout. and again, in our data it's given as float|
|'TUE'| Time using <br>technology devices| TUE is between 0 to 2. I think question will be "How long you have <br>been using technology devices to track your health." in our data it's given as float |
|'CALC'| Consumption of alcohol | Takes 3 values: `Sometimes`, `no`, `Frequently`|
| 'MTRANS' | Transportation used| MTRANS takes 5 values `Public_Transportation`, `Automobile`, <br>`Walking`, `Motorbike`, & `Bike`|
|'NObeyesdad'| TARGET | This is our target, takes 7 values, and in this comp. we have to give <br>the class name (Not the Probability, which is the case in most comp.)

<br>

<div style="font-size:120%"> 
    <b>NObeyesdad (Target Variable):</b>
</div>

* Insufficient_Weight : Less than 18.5
* Normal_Weight       : 18.5 to 24.9
* Obesity_Type_I      : 30.0 to 34.9
* Obesity_Type_II     : 35.0 to 39.9
* Obesity_Type_III   : Higher than 40
* Overweight_Level_I, Overweight_Level_II takes values between 25 to 29

<div style="font-size:120%"> 
    <b>Files:</b>
</div>

- **train.csv** - the training dataset; NObeyesdad is the categorical target
- **test.csv** - the test dataset; your objective is to predict the class of NObeyesdad for each row
- **sample_submission.csv** - a sample submission file in the correct format

<hr>

<div align="center">
<br><p align="centre"><b>Contagem de visitantes</b></p>  
<p align="center"><img align="center" src="https://profile-counter.glitch.me/{Obesity_Risk_Prediction_and_Analysis}/count.svg" /></p> 
<br>  

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=87CEFA&height=120&section=footer"/>**** 
</div>
