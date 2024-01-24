# Charity_Funding_Predictor
 Predicting the success of funding applicants for a charitable organization using machine learning and predictive modeling. The project involves creating a binary classification model using deep learning techniques.


## Overview of the Analysis

The purpose of this analysis was to develop a deep learning model for predicting the success of organizations applying for funding from Alphabet Soup. The objective was to assess the effectiveness of funding usage based on various features provided in the dataset.


![Alt text](images/1_deep_learning.jpg)


The model is trained on a dataset comprising information from over 34,000 organizations that have previously received funding from Alphabet Soup, encompassing relevant metadata for each organization.


## Results

### Data Preprocessing

**Target variable(s) for the model:** The model focuses on predicting the `IS_SUCCESSFUL` variable.

**Feature variable(s) for the model:** The model incorporates various feature variables such as `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, and `ASK_AMT`.

**Variable(s) removed from the input data:** The `EIN` and `NAME` columns were excluded from the input data as they serve as identification columns and do not contribute as features or targets.

**Inclusion of `NAME` in the last model:** The feature variable `NAME` has been reintroduced in the final model.


### Compiling, Training, and Evaluating the Model


![Alt text](images/2_train_model.png)


**Number of Neurons:** Configured with varying numbers based on experimentation.

**Layers:** Multiple hidden layers were added to capture complex patterns.

**Activation Functions:** ReLU for hidden layers and Sigmoid for the output layer (binary classification).

**Model Performance:**
Achievement of Target Model Performance: Achieved a satisfactory balanced accuracy, precision, and recall.

**Steps to Increase Model Performance:**
- **Iterative Tuning:** Adjusted the number of neurons, layers, and activation functions iteratively.
- **Optimization Techniques:** Experimented with different optimizers and learning rates.
- **Regularization:** Implemented dropout layers for regularization.
- **Epochs:** Increased the number of epochs to allow for more training.







## Author

## [Jalees Moeen GitHub](https://github.com/JaleesMoeen)



