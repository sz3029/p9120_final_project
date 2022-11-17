# P9120 Final Project
* Author: Shihui Zhu

## Topic: Active learning in imbalanced dataset

I. Aim
* Many machine learning methods are built upon the assumption that the dataset is balanced. 
However, real world datasets are often imbalanced, which hinders the learning performance of many algorithms. 
Current resampling methods are either under-sampling or over-sampling, which is computational expensive 
and often causes problems such as overfitting. Active learning seems to address the problem by querying 
on small pool of data each time. We can edit the algorithm to make it select important majority-class 
instances and generating informative minority-class instances at iteration. This project aims to compare 
and contrast the performance of an adapted active learning model with 1) balanced random forest, 2) adaboost 
and 3) neutral network models trained on resampled datasets of an imbalanced dataset 
on certain metrics (precision-recall, g-means etc. al.).

II. Method
* The method to investigate is active learning algorithms adapted with alternative performing important 
sampling (ALIS), which consists of selecting important majority-class instances and generating 
informative minority-class instances (Xinyue, etc., al.). The base estimator at each iteration 
will be SVM.

III. Dataset I Plan to Use

* The data I plan to use in this project is the Credit Card Fraud Detection from the Kaggle dataset. 
It consists of 164 columns, which includes numeric, categorical and binary columns from the risk
analysis profile of a credit card company. The dataset has a binary outcome and it is highly
imbalanced (positive class 91.93%, negative class 8.07%).

IV. Reference

* Wang, Xinyue., etc. al. “Important sampling based active learning for imbalance classification.” Springer. Science China. <https://link.springer.com/article/10.1007/s11432-019-2771-0>.
* Kaggle Dataset: https://www.kaggle.com/datasets/mishra5001/credit-card

