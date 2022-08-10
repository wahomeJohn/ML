# TANZANIA WATERPOINTS FUNCTIONALITY PREDICTIONS USING MACHINE LEARNING MODELS.

BUSINESS PROBLEM

The Ministry of Water in Tanzania needs to ensure that clean, potable water is available to Tanzania's inhabitants.
The water problem can be easily solved with knowledge of the functionality of the different waterpoints.
Classifying the functionality of a wter point to be either functional, functional but needs repair or non functional,
assist the government know the waterpoints that either need improvement, or those that are functional.
If we can accurately classify a waterpoint, the Ministry will have a better understanding of their existing infrastructure, 
and because of cost savings, will be able to reallocate existing resources to expand the water infrastructure.

DATA

Data
Data is provided by Taarifa and the Tanzanian Ministry of Water originally as part of a competition hosted by DrivenData.

It contains approximately 60,000 instances.

It is stored in a csv file.

Methodology
Exploratory Data Analysis of the dataset to understand each data feature among each other and to the labels.

Clean the data and impute data for the significant amount of missing data in the dataset. The data did not appear to be intentionally left out, 
instead it was not available when the data collection took place, or the data collection was not rigorous enough.

The dataset is highly imbalanced, oversampling will be needed to create synthetic data to balance the clases.

Implement Supervised Learning Classifiers.
Four classifiers were implemented and the best performing had its hyperparameters tuned. 
Random Forest was the best performing and the others were Logistic Regression, KNN with SMOTE oversampling, Decision Tree, and RandomForest with GridSearchCv.

Model Performance
Performance was judged on overall accuracy and balanced recall.

After tuning the Random Forest Classifier. 

Recomendations
Use the model to prioritize site visits. Priority should be given to maintenance staff sent to waterpoints that are predicted to be functional but in need of repair or non functional.

The Ministry can use the cost savings from a more efficient maintenance operation to expand the water infrastructure.

The Ministry can use the accuracy of the model and its improved maintenance program as a selling point when soliciting international aid.

Future Work
Alot of missclassification was present. This should be the basis of future work
