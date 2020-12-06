<h1>Predicting the Onset of cardiovascular disease</h1>
<h2>by Abdul, Chaokai, Winnie and Trusting</h2>
<p>We design a Cardiovascular Disease onset prediction​ tool that will help in predicting onset of Cardiovascular disease given a patients’ clinical information. </p>
<p>Cardiovascular disease is the leading cause of death among people in the US. According to the National Vital Statistics, about 854,390 people died due to Cardiovascular Disease in 2019 only (CDC, 2019). Despite this high mortality rate, health care service in the US is expensive and so providing a means in which people could detect (easily and possibly early) if they have a Cardiovascular disease or not would help in early treatment, lesser medical expenses and would increase chances of survival. Our proposed Cardiovascular Disease Onset Prediction tool would be used by medical personnel to detect Cardiovascular disease easily and faster. The current system only allows qualified personnel to collate patients’ clinical information and make decision – which usually take a longer time – on whether a patient has been diagnosed with Cardiovascular disease or not.  </p>
<p>Our Cardiovascular Disease onset prediction​ tool will help in predicting onset of Cardiovascular disease given a patients’ clinical information. </p>

<h3>Our Approach</h3>
<h4>Step 1: Data Extraction:</h4>
<p>We intend getting our dataset from the Kaggle https://www.kaggle.com/sulianova/cardiovascular-disease-dataset (Ulianova, n.d.). it has 70,000 records of patients’ data with 11 features –both numerical and categorical.</p>
<h4> Step 2: Data Cleaning and Exploration:</h4> 
<p>
We will clean and explore our dataset to remove missing, redundant and inconsistent data as this may increase noise which may affect prediction accuracy of our tool.  
</p>
<h4> Step 3: Data Pre-processing: </h4>
<p>
After cleaning and exploring data, we will select features, and then regularize and standardize the data before applying Machin learning models. Our unique filter combining ANOVA and cost efficiency will be applied for this data preprocessing process. 
</p>
<h4>Step 4: Modelling using Machine Learning Algorithms</h4>
<p>
Since our target is binary, we plan to use algorithms that will classify binary outcomes, that is, whether a patient has cardiovascular disease or not. We plan to use the Logistic regression, KNN, Decision tree, random forest classifier, Support Vector Classifier, Perceptron as well as Convolutional Neural network for prediction. We will use optimizer methods for the models by tuning them with different hyperparameter measures for performance improvement. We will also apply 10-fold cross-validation to each of the models to ensure the models perform the best result. 
</p>
<p>Then we will make a hybrid model by combining (averaging) algorithms that give us better performance with respect to accuracy and ROC-AUC. This hybrid model will be used on the test data.</p>
