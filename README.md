# Credit_Risk_Analysis

Supervised Machine Learning 

## Project Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalance classes. The imbalanced-learn and scikit-learn libraries were used to build evaluate models using resample. 


### Results 

#### RandomOverSampler Model

![fig1.png]( https://github.com/AjaniBenoit/Credit_Risk_Analysis/blob/main/image/fig1.png)

1. Balanced Accuracy is 0.6533977140416822
2. The precision for high risk loans is 0.01 with a sensitivity of 0.63. The precision for low risk loans is 1.00 with a sensitivity of 0.67. 

#### SMOTE MODEL 

![fig2.png]( https://github.com/AjaniBenoit/Credit_Risk_Analysis/blob/main/image/fig2.png)

1. Balanced Accuracy is 0.6512291961274883
2. The precision for high risk loas is 0.01 with a sensitivity of 0.64. The precision for low risk loans is 1.00 with a sensitivity of 0.66

#### Undersampling 

![fig3.png]( https://github.com/AjaniBenoit/Credit_Risk_Analysis/blob/main/image/fig3.png)

1.  Balanced Accuracy is 0.6512291961274883
2. The precision for high risk loas is 0.01 with a sensitivity of 0.61. The precision for low risk loans is 1.00 with a sensitivity of 0.45. 

#### Combination (Over and Under) Sampling 

![fig4.png]( https://github.com/AjaniBenoit/Credit_Risk_Analysis/blob/main/image/fig4.png)

1.  Balanced Accuracy is 0.5292150629907619
2. The precision for high risk loas is 0.01 with a sensitivity of 0.70. The precision for low risk loans is 1.00 with a sensitivity of 0.57. 

