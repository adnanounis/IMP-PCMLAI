# IMP-PCMLAI
# Breast Cancer Identification using a Decision Tree Model


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
A decision tree classification model was trained on patient data from clinical studies conducted by Dr. William Wolberg. The goal of this model is to correctly identify whether the patient has a benign or malignant tumor in the breast area.
## DATA
The data used is patient data from clincal studies conducted by Dr. William Wolberg in Wisconsin in the United States of America. The data is publicly available online and covered by a (CC BY 4.0) license and is currently hosted on UC Irvine's Machine learning repository.
The link to the dataset can be found here: https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original

## MODEL 
A decision tree classification model was used in this case as decision trees excel in classification tasks and are robust enough to deal with a variety of different data types if necessary. Furthermore, implementing a decision tree classification model is relatively simple
yet very effective and can produce great results. 

## HYPERPARAMETER OPTIMSATION
The hyperparameters were optimized using grid search cross validation. The following hyperparameters were optimized using this strategy (criterion,max_depth, splitter,max_features)

## RESULTS
The model implemented produced great results reaching accuracy of up to 95%. Other performance metrics were used and a small discussion of the performance and limitations of the model is discussed in further details in the model card file.
The model is able to predict whether a breast tumor is malignant or benign given a set of biological readings that are outlined in the datasheet and model card. (The limitations of the model are also discussed there). 


