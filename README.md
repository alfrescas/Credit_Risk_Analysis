# Credit Risk Analysis
## Overview:

Jill wants to use imbalanced-learn and scikit-learn libraries to evaluate models using resampling. Their will be a comparision of two machine learning models that reduce bias, using RandomOverSampler, SMOTE algorithms, and undersample the data usig ClusterCentroids algorithm. To predict credit risk we will use BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results:

The credit risk resampling, after printing out the results for the imbalanced classification report (as shown below). The prediction score results is showing that it is not reliable to trust. The score of 0.01 for the high risk predictions indicates that this is not a very usuable machine learning model. 

<img width="521" alt="image" src="https://user-images.githubusercontent.com/107371010/206880679-fdc0db6d-12c9-4038-b960-45c1e0a8c543.png">

For the _SMOTE Oversampling_ , the image below shows some slight differences from the previous score for the image above. The prediction scores for the SMOTE Oversampling cannot be usuable as well.

<img width="626" alt="image" src="https://user-images.githubusercontent.com/107371010/206880789-59656ae4-c2dc-47b7-a587-9a932e1ad4cb.png">

The next image shows the results for the _Undersampling_ algorithms, the results haven't changed scores for the high risk and low risk sections. 

<img width="536" alt="image" src="https://user-images.githubusercontent.com/107371010/206880868-1a6f0ce5-cccb-433e-9849-3cff88cb5fdb.png">

Using the combination of Over and Under Sampling shows better results for the F1 with an increase of 0.01, visual shown below:

<img width="527" alt="image" src="https://user-images.githubusercontent.com/107371010/206881045-0a45d0fb-2b6f-4514-9145-c498464bc37d.png">

The results for the Credit Risk Ensemble, show better results for the machine learning model. Below are the scores using the Balanced Random Forest Classifier:

<img width="506" alt="image" src="https://user-images.githubusercontent.com/107371010/206881171-2e2d8b98-2301-48a7-8e4f-0c67dc4affad.png">

Using Easy Ensemble AdaBoost Classifier yielded the best results for the machine learning model, the results are significantly higher than the previous machine learning models. the results:

<img width="512" alt="image" src="https://user-images.githubusercontent.com/107371010/206881318-04a855ce-3d58-4235-97a5-20567997e51c.png">

## Summary:

Based on the scores for each machine learning model, the high risk prediction results are all of the machine learning models score very low. Which means that we cannot rely on these high risk predictions. The last machine learning model _Easy Ensemble AdaBoost Classifier_, would be the machine learning model I would recommend to use out of all the ones used in this analysis. 
