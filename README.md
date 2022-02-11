# Classification_prediction_model_of_teaching_assistant_assessment 
# Objective

The objective of this project is to determine the best classification model that can classify the performance of the teaching assistant based on 5 attributes given in the dataset with high accuracy. Such results can be used to make decisions to improve the performance of TAs.

# Strategy

The following classification models will be compared:
* KNN (K Nearest Neighbours)
* SVM (Support Vector Machines)
* Decision Trees

The best classification model would determined after comparison based on multiple parameters such as:
* Precision
* Recall
* F1-score

# Justification

* Since the dataset is highly categorical, it is a good idea to use a classification model that can categorize the performance of a teaching assistant efficiently with least scope of error

* We have employed few of the most commonly used classification models for this purpose that can be conveniently implemented

* Results of this project can help in decision making by predicting the performance of incoming TAs

# Results

## Accuracy
1. KNN ~ 39.9%
<img width="283" alt="image" src="https://user-images.githubusercontent.com/86041798/153545586-a5f5fe16-6c7c-446c-b77b-28104a2026c0.png">
2. Linear SVM: ~52.17%
<img width="272" alt="image" src="https://user-images.githubusercontent.com/86041798/153545594-d06dfcfd-da1f-4147-b2ab-6052ba9db6ca.png">
3. Radial SVM: ~34.78%
<img width="266" alt="image" src="https://user-images.githubusercontent.com/86041798/153545602-265bc513-6e8c-40cd-be14-e8033a8c30a3.png">
4. Decision Trees: ~80.43%
<img width="498" alt="image" src="https://user-images.githubusercontent.com/86041798/153545606-5615af13-3847-48ae-9f27-fb36ffe03f09.png">





## Precision,Recall,and F1-score

Decision Tree
<img width="295" alt="image" src="https://user-images.githubusercontent.com/86041798/153545760-517772f7-d975-4552-b193-1fe0edd33b4e.png" title = "Decision Tree">
KKN
<img width="325" alt="image" src="https://user-images.githubusercontent.com/86041798/153545763-d9d7cf8d-2094-405f-a598-f340dbd33430.png" title = "KNN">
Radial SVM
<img width="269" alt="image" src="https://user-images.githubusercontent.com/86041798/153545777-07b59937-4f10-4a9b-aff4-8588b09f7fe8.png" title = "Radial SVM">
Linear SVM
<img width="268" alt="image" src="https://user-images.githubusercontent.com/86041798/153545780-d24242c0-8ad1-48de-a724-55cd374f7ee4.png" title = "Linear SVM">










