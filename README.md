<h1>Predicting the Onset of cardiovascular disease</h1>
<h2>by Abdul, Chaokai, Winnie and Trusting</h2>
<p align="justify">We design a Cardiovascular Disease onset prediction​ tool that will help in predicting onset of Cardiovascular disease given a patients’ clinical information. </p>
<p align="justify">Cardiovascular disease is the leading cause of death among people in the US. According to the National Vital Statistics, about 854,390 people died due to Cardiovascular Disease in 2019 only (CDC, 2019). Despite this high mortality rate, health care service in the US is expensive and so providing a means in which people could detect (easily and possibly early) if they have a Cardiovascular disease or not would help in early treatment, lesser medical expenses and would increase chances of survival. Our proposed Cardiovascular Disease Onset Prediction tool would be used by medical personnel to detect Cardiovascular disease easily and faster. The current system only allows qualified personnel to collate patients’ clinical information and make decision – which usually take a longer time – on whether a patient has been diagnosed with Cardiovascular disease or not.  </p>
<p align="justify">Our Cardiovascular Disease onset prediction​ tool will help in predicting onset of Cardiovascular disease given a patients’ clinical information. </p>

<h3>Our Approach</h3>
<h4>Step 1: Data Extraction:</h4>
<p align="justify">Our dataset is from the Kaggle https://www.kaggle.com/sulianova/cardiovascular-disease-dataset (Ulianova, n.d.). it has 70,000 records of patients’ data with 11 features –both numerical and categorical.</p>
<h4> Step 2: Data Cleaning and Exploration:</h4> 
<p align="justify">We cleaned and explored our dataset to remove missing, redundant and inconsistent data as this may increase noise which can affect prediction accuracy of our tool</p>
<h4> Step 3: Data Pre-processing: </h4>
<p align="justify">After cleaning and exploring data, we selected features, and then regularize and standardize the data before applying Machin learning models. Our unique filter combining ANOVA and cost efficiency will be applied for this data preprocessing process.</p>
<h4>Step 4: Modelling using Machine Learning Algorithms</h4>
<p align="justify">Since our target is binary, we used algorithms that will classify binary outcomes, that is, if a patient has cardiovascular disease or not. We used Machine learning algorithms including Naive Bayes, XGBoost, KNN, Decision tree, random forest classifier, Support Vector Classifier, Perceptron as well as Convolutional Neural network for prediction. We used optimizer methods for the models by tuning them with different hyperparameter measures for performance improvement. We also apply 10-fold cross-validation to each of the models to ensure the models perform the best result.</p>
<h4>Step 5: Hybrid Algorithm</h4>
<p align="justify">Finally, we combined our different algorithms to make a hybrid model by combining (averaging) algorithms that gave us better performance with respect to accuracy, confusion matrix, f1 score and ROC-AUC. This hybrid model will be used on the test data.</p>
