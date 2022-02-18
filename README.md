# Supervised Machine Learning and Credit Risk Analysis

## Overview
This project utilized six machine learning models applied to credit risk, an inherently unbalanced classification problem that requires differentiating large numbers of good loans from a much smaller number of risky loans.

## Results

* Naive Random Oversampling: This algorthm produced a balanced accuracy score of 66%, with precision of 99% and recall of 60%.

<img width="708" alt="Screen Shot 2022-02-18 at 1 26 15 PM" src="https://user-images.githubusercontent.com/91562577/154741143-819e0db2-fc78-4018-b854-bac6d250c81a.png">

* SMOTE Oversampling: This option produced results similar to Naive Random Oversampling, with a balanced accuracy score of 66%, precision of 99% and recall of 69%.

<img width="709" alt="Screen Shot 2022-02-18 at 1 26 53 PM" src="https://user-images.githubusercontent.com/91562577/154741215-6038bc73-cc84-4ffa-a944-c4400b0f89a5.png">

* ClusterCentroids Undersampling: Again, a comparable balanced accuracy score of 66% and precision of 99%, but with a much lower recall of 40%.

<img width="706" alt="Screen Shot 2022-02-18 at 1 27 50 PM" src="https://user-images.githubusercontent.com/91562577/154741355-41b55829-1c03-480d-8dd8-57c84ff5a5ee.png">

* SMOTEEN Combination Sampling: This method produced a lower balanced accuracy score of 54%, with precision of 99% and mediocre recall of 58%.

<img width="709" alt="Screen Shot 2022-02-18 at 1 28 57 PM" src="https://user-images.githubusercontent.com/91562577/154741500-390d9fb5-b7c6-4244-8835-e70f78405783.png">

* Balanced Random Forest Classifier: This algorithm saw a higher balanced accuracy score of 79%, with precision of 99% and high recall of 87%.

<img width="704" alt="Screen Shot 2022-02-18 at 1 30 42 PM" src="https://user-images.githubusercontent.com/91562577/154741745-02dfbf5d-558f-41cf-a377-91383ac27828.png">

* Easy Ensemble AdaBoost Classifier: This approach had the best overall results, with a the highest balanced accuracy score of 93%, precision of 99%, and highest recall of 94%.

<img width="716" alt="Screen Shot 2022-02-18 at 1 31 17 PM" src="https://user-images.githubusercontent.com/91562577/154741837-c3b263c8-84da-4d95-860c-98b2fe134f3c.png">




## Summary

