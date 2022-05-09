# Credit_Risk_Analysis
### Machine Learning Analytics Using LedingClub Dataset

## Overview of the analysis:

### This analysis involved the application of supervised machine learning algorithms, specifically in the area of credit risk analysis. Different techniques were employed to train and evaluate models with unbalanced classes. *imbalance-learn* and *scikit-learn* libraries were also utilized to build and evaluate models using resampling. The dataset used in this analysis was obtained from LendingClub.

## Results:

## **Oversampling**

<p align="center">
   Naive Random Oversampling
</p>

![This is an image](https://github.com/gmgarin/Credit_Risk_Analysis/blob/0d733f3c6ed44b050fb59369c6da65fc86635f00/images/image1.png)

- The accuracy rate is at 64.5% while precision rate and recall rate are 1.0% and 73.0% respectively for "high risk" and 100.0% and 57.0% respectively for "low risk"

<p align="center">
  SMOTE Ovesampling
</p>

![This is an image](https://github.com/gmgarin/Credit_Risk_Analysis/blob/0d733f3c6ed44b050fb59369c6da65fc86635f00/images/image2.png)
- The accuracy rate is at 66.2% while precision rate and recall rate are 1.0% and 63.0% respectively for "high risk" and 100.0% and 69.0% respectively for "low risk"

## **Undersampling**

<p align="center">
  Undersampling
</p>

![This is an image](https://github.com/gmgarin/Credit_Risk_Analysis/blob/0d733f3c6ed44b050fb59369c6da65fc86635f00/images/image3.png)
- The accuracy rate is at 54.4% while precision rate and recall rate are 1.0% and 69.0% respectively for "high risk" and 100.0% and 40.0% respectively for "low risk"


## Combination Sampling

<p align="center">
  Combination Sampling
</p>

![This is an image](https://github.com/gmgarin/Credit_Risk_Analysis/blob/0d733f3c6ed44b050fb59369c6da65fc86635f00/images/image4.png)
- The accuracy rate is at 65.3% while precision rate and recall rate are 1.0% and 73.0% respectively for "high risk" and 100.0% and 57.0% respectively for "low risk"

## Balanced Random Forest Classifier

p align="center">
 Balanced Random Forest Classifier
</p>

![This is an image](https://github.com/gmgarin/Credit_Risk_Analysis/blob/0d733f3c6ed44b050fb59369c6da65fc86635f00/images/image5.png)
- The accuracy rate is at 79.9% while precision rate and recall rate are 3.0% and 70.0% respectively for "high risk" and 100.0% and 87.0% respectively for "low risk"

## Easy Ensemble AdaBoost Classifier

<p align="center">
  Easy Ensemble AdaBoost Classifier
</p>

![This is an image](https://github.com/gmgarin/Credit_Risk_Analysis/blob/0d733f3c6ed44b050fb59369c6da65fc86635f00/images/image6.png)
- The accuracy rate is at 79.9% while precision rate and recall rate are 3.0% and 70.0% respectively for "high risk" and 100.0% and 87.0% respectively for "low risk"