# Model Card (Decision Tree Classification Model for breast cancner identification) 

 

## Model Description

**Input:**  (Clump Thickness, Uniformity of Cell Size, Uniformity of Cell Shape, Marginal Adhesion, Single Epithelial Cell Size, Bare Nuclei, Bland Chromatin, Normal Nuceoli, Mitoses) These are Biological measurements for each patient. Each instance represents the data for an individual patient.

**Output:** A binary output of 0 or 1. The binary outputs represent the breast cancer being benign or malignant respectively.

**Model Architecture:** A decision tree classification model was used. The model was tuned using grid search to find the optimal values for the following hyperparameters (criterion,max_depth,splitter,max_features)

## Performance

The performance of the model was evaluated using a confusion matrix. From the confusion matrix the following metrics were computed:

sensitivity: 0.8840579710144928
specificity: 0.9852941176470589
accuracy: 0.9512195121951219
misclassification rate: 0.04878048780487809
precision: 0.9682539682539683 


## Limitations

The model should only be used for the classification of breast cancer (malignant or benign) in the Wisconsin area. All the datapoints were sampled from there meaning that the model can't be used to objectively evaluate other population centers. 
Furthermore, the dataset the model was trained on is relatively small. As a result of this, the training and testing data used is also small. More data is needed to avoid overfitting and more data from other population centers is required to make this model more objective. 


## Trade-offs

The model seems to perform well based on the performance metrics. However, due to the small size of the dataset overfitting might be a concern. The model was tuned using using grid search to find the optimal parameters in an effort to have the best decision tree classifier and also to reduce any overfitting.
The model also is better at identifying benign cases than it is at identifying malignant ones as seen by the specificity and sensitivity values. 
