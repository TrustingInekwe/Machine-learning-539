<h1>Predicting the Onset of cardiovascular disease</h1>
<h2>by Abdul, Chaokai, Winnie and Trusting</h2>

![heartdiseasepic](https://user-images.githubusercontent.com/55979883/101299304-bd79db00-37ff-11eb-837f-2b42b7b4d399.jpeg)

<p align="justify">Cardiovascular disease is the leading cause of death among people in the US. According to the National Vital Statistics, about 854,390 people died due to Cardiovascular Disease in 2019 only (CDC, 2019). Despite this high mortality rate, health care service in the US is expensive and so providing a means in which people could detect (easily and possibly early) if they have a Cardiovascular disease or not would help in early treatment, lesser medical expenses and would increase chances of survival. Our proposed Cardiovascular Disease Onset Prediction tool would be used by medical personnel to detect Cardiovascular disease easily and faster. The current system only allows qualified personnel to collate patients’ clinical information and make decision – which usually take a longer time – on whether a patient has been diagnosed with Cardiovascular disease or not.</p>
<p align="justify"><p align="justify">We design a Cardiovascular Disease onset prediction​ tool that will help in predicting onset of Cardiovascular disease given a patients’ clinical information. 


<h3>Our Approach</h3>
<h4>Step 1: Data Extraction:</h4>
<p align="justify">Our dataset is from the Kaggle https://www.kaggle.com/sulianova/cardiovascular-disease-dataset (Ulianova, n.d.). it has 70,000 records of patients’ data with 11 features –both numerical and categorical.</p>

<h4> Step 2: Data Pre-processing: </h4>
<p align="justify"> Our data processing involved three steps namely:</p>

<h5>i. Checking for missing or NaN values</h5>
<p align="justify">As a first step in our data processing, we looked for Nan values of which we didn't find any. We had a dataset that was complete and numeric</p>

<h5>ii. Checking if our dataset is balanced</h5>
<p align="justify">Secondly, we checked to see if our dataset was balanced. Our dataset had a Positive to Negative ratio of 34979 to 35021 indicating an almost balanced dataset. </p>
  
<h5>iii. Removing outliers</h5>
<p align="justify"> Our dataset contained outliers for some of the features. For example, for the various blood pressure categories of Normal, Elevated and Hypertensive stages [1], we searched for values that didnt fall within the acceptable  Systolic (upper) and Diastolic (lower) ranges. For our Systolic Blood Pressure feature, we set our outliers values to those that were less than or equal to 80 or greater than 200 of which we had over 307 cases.</p>  

![systolic](https://user-images.githubusercontent.com/55979883/101304835-30d71900-380f-11eb-88e5-f2b16052c61c.png)

<p align="justify">For Diastolic Blood Pressure feature, we set our outliers values to those that were less than 50 or greater than 1032 of had over 1032 cases.</p>

![Diastollic](https://user-images.githubusercontent.com/55979883/101304808-2288fd00-380f-11eb-9448-649991590ff4.png)

<p align="justify">For weight feature, we set our outliers values to those that were less than or equal to 30 of had over 7 cases.</p>

![Weight](https://user-images.githubusercontent.com/55979883/101305205-22d5c800-3810-11eb-88b0-46836c651faa.png)

<p align="justify">For height feature, we set our outliers values to those that were less than or equal to 100 of had over 29 cases.</p>

![Height](https://user-images.githubusercontent.com/55979883/101305046-b22eab80-380f-11eb-81d7-b81f6ca0580e.png)


<h4>Step 4: Modelling using Machine Learning Algorithms</h4>
<p align="justify">We used Machine learning algorithms including Naive Bayes, XGBoost, KNN, Decision tree, random forest classifier, Support Vector Classifier, Perceptron as well as Convolutional Neural network for prediction. We used optimizer methods for the models by tuning them with different hyperparameter measures for performance improvement. We also apply 10-fold cross-validation to each of the models to ensure the models perform the best result.</p>

<table style="width:100%">
  <caption>Model Algorithms implemented</caption>
  <tr>
    <td>K Nearest Neighbour</td>
    <td>Logistic Regression</td>
    <td>Decision Tree Classifier</td>
    <td>Random Forest Classifier</td>
    <td>Extra Tree Classifier</td>
    <td>Support Vector Classifier</td>
    <td>Naive Bayes</td>
  </tr>
  <tr>
    <td>Multinomial Naive Bayes</td>
    <td>Bagging Classifier</td>
    <td>AdaBoost Classifier</td>
    <td>XGBoost Classifier</td>
    <td>Neural Networks</td>  
  </tr>
</table>
<p align="justify">The figure below is a list of models we used and their accuracy values</p>

![model_performance2](https://user-images.githubusercontent.com/55979883/101528076-cd5b0180-395c-11eb-9b49-12a6cbb1fdee.png)

<p align="justify">The figure below is the AUC ROC for models we used</p>

![prediction_result](https://user-images.githubusercontent.com/55979883/101528002-b9170480-395c-11eb-83cd-0fbd58bc048d.png)

<h4>Step 5: Hybrid Algorithm</h4>
<p align="justify">Finally, we selected some of our best models namely; Support Vextor Classifier, Logistic Regression and Adaboost to make a hybrid model so we can have a better performance with respect to accuracy, confusion matrix, f1 score and ROC-AUC. This hybrid model will be used on the test data and for our widget.</p>


<h3>Online Source</h3>
<p> 1. https://www.heart.org/en/health-topics/high-blood-pressure/understanding-blood-pressure-readings </p>
