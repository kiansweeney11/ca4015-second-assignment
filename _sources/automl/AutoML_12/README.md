# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_DecisionTree](1_DecisionTree/README.md)                         | Decision Tree     | logloss       |      0.386876  |        36.19 |
|              | [2_Linear](2_Linear/README.md)                                     | Linear            | logloss       |      0.0940139 |        22.58 |
| **the best** | [3_Default_Xgboost](3_Default_Xgboost/README.md)                   | Xgboost           | logloss       |      0.0499862 |        30    |
|              | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | logloss       |      0.777886  |        33.89 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | logloss       |      0.550311  |         6.51 |
|              | [Ensemble](Ensemble/README.md)                                     | Ensemble          | logloss       |      0.0499862 |         0.37 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

