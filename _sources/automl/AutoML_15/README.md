# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_DecisionTree](1_DecisionTree/README.md)                         | Decision Tree     | logloss       |      0.840242  |        27.3  |
|              | [2_Linear](2_Linear/README.md)                                     | Linear            | logloss       |      0.330437  |        22.2  |
| **the best** | [3_Default_Xgboost](3_Default_Xgboost/README.md)                   | Xgboost           | logloss       |      0.0893175 |        27.18 |
|              | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | logloss       |      0.722411  |        25.78 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | logloss       |      1.33566   |         6.17 |
|              | [Ensemble](Ensemble/README.md)                                     | Ensemble          | logloss       |      0.0893175 |         0.34 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

