# Santander-Customer-Satisfaction-Competition

-- This is a gradient decision tree trained by me and two other teammates, Yizhou Feng and Shuangchen Shen, for a Kaggle competition. 

-- The link to the competition is here: https://www.kaggle.com/c/santander-customer-satisfaction

-- This gradient decision tree uses extreme gradient boosting model (http://xgboost.readthedocs.io/en/latest/model.html).

-- Irrelevant features (such as zero values and uniform values) are ignored during the training phase to reduce the amount of calculation.

-- Features that are not quite relevant are also excluded by using an Extra Trees Classifier.
