# sampling-Puranjay
This is a submission for the Assignment: Sampling, of UCS654(Predictive Analytics using Statistics).

## About the project:
- This project uses this [dataset](https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv).
- It was a highly imbalanced dataset. Two target classes, 1 and 0 were in the ratio 0.1179. 
- Hence, Random Oversampling has been used to balance the imbalanced dataset. 
  Random oversampling involves randomly duplicating examples from the minority class and adding them to the training dataset.<br><br>
- 5 different sampling techniques have been used on the dataset, which are:
1. Simple random sampling
2. Stratified sampling
3. Cluster sampling
4. Systematic sampling
5. Reservoir sampling<br>
- The above samples produced were then trained on 5 different ML models, which are:
1. Random forest
2. Decision tree
3. Logistic Regression
4. SVC
5. K-Nearest Neighbors<br>
## Final results:
Comparing the accuracies achieved by all the models:
|      | Simple Random | Stratified | Cluster | Systematic | Reservoir |
|------|------- |------------|---------|------------| ------------ |
| Random Forest |  99.60% |    99.60%   |  53.76%  |    99.73%  |      99.40%        |
| Decision Tree |  93.05% |    93.65%   |  53.37%   |    93.45%   |      92.06%        | 
| KNN |  93.05% |    95.23%  |  53.37%  |   93.65%     |     93.05%     |  
| Logistic Regression |  91.26% |    91.86%  |  52.38%  |    91.46%   |  92.85%            |
| SVC |  82.53% |    93.56%   |  45.63  |    64.48%   |        56.34%      |

## Conclusion:
Random forest Classifier is consistently working well in all the sampling techniques and producing the highest accuracy in every sampling method.
