# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_DecisionTree](1_DecisionTree/README.md)                         | Decision Tree     | logloss       |       2.41222  |        29.09 |
| **the best** | [2_Linear](2_Linear/README.md)                                     | Linear            | logloss       |       0.666864 |        27.87 |
|              | [3_Default_Xgboost](3_Default_Xgboost/README.md)                   | Xgboost           | logloss       |       1.33691  |        31.28 |
|              | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | logloss       |       1.00787  |        24.43 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | logloss       |       1.61741  |         6.82 |
|              | [Ensemble](Ensemble/README.md)                                     | Ensemble          | logloss       |       0.666864 |         0.53 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

