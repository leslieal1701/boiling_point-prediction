# boiling_point-prediction
Code for the development of machine learning regression models to predict normal boiling point using quantitative-structure property (QSPR) approach


Normal boiling point is one of the most important thermal properties used to characterize and identify compounds. However, obtaining experimental 
boiling point data can be difficult due to the high cost and time-consuming nature of carrying out laboratory tests. In this work, two quantitative 
structure−property relationship (QSPR) models were built based on existing experimental data and molecular descriptors through the use of artificial 
neural network (ANN) and extreme gradient boosting (XGBoost) machine learning methods. For each model, the database was divided into two subsets: 80% 
for the training set and 20% for the test set.  Python cheminformatics modules were used to generate a set of 33 molecular descriptors that were subsequently 
subjected to feature reduction methods in order to obtain an optimal set containing the 6 most significant descriptors. These selected molecular descriptors 
were used as input features for the ML models. Both models were validated to have satisfactory performances in terms of  goodness-of-fit, internal robustness,
andexternal predictive ability.
