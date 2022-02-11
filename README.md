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

1. Decision Tree
<img width="295" alt="image" src="https://user-images.githubusercontent.com/86041798/153545760-517772f7-d975-4552-b193-1fe0edd33b4e.png">
2. KNN
<img width="325" alt="image" src="https://user-images.githubusercontent.com/86041798/153545763-d9d7cf8d-2094-405f-a598-f340dbd33430.png">
3. Radial SVM
<img width="269" alt="image" src="https://user-images.githubusercontent.com/86041798/153545777-07b59937-4f10-4a9b-aff4-8588b09f7fe8.png">
4. Linear SVM
<img width="268" alt="image" src="https://user-images.githubusercontent.com/86041798/153545780-d24242c0-8ad1-48de-a724-55cd374f7ee4.png">

<br/>

We observe that For Decision Tree:
## Overall Prediction Accuracy:  80.43% (high)
* Precision of Class 1: 80%
* Precision of Class 2: 75%
* Precision of Class 3: 90% 
## Recall:
* Recall of Class 1: 89%
* Recall of Class 2: 80%
* Recall of Class 3: 69% 
## F1-score: Balance between Precision and Recall
* F1-score of Class 1: 84%
* F1-score of Class 2: 77%
* F1-score of Class 3: 78%




# Decision Tree Diagram
<img width="721" alt="image" src="https://user-images.githubusercontent.com/86041798/153547003-f5220ae8-1edd-4caf-9fee-234c1267b436.png">


# Conclusion

After our analysis we find that Decision Tree is the best classification model amongst the 3 implemented ones for the given dataset in order to predict the performance of a teaching assistant (TA). This is because after testing the data using this model we obtain a high accuracy score, precision, recall, f1-score as well as the highest sensitivity for the Decision Tree Classification model.







