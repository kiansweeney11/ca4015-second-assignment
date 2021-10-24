# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                                 | Baseline          | rmse          |         253098 |         1.18 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                         | Decision Tree     | rmse          |         255857 |         5.04 |
|              | [3_Linear](3_Linear/README.md)                                     | Linear            | rmse          |         264675 |         2.5  |
| **the best** | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | rmse          |         242098 |         3.83 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | rmse          |         278029 |         1.63 |
|              | [Ensemble](Ensemble/README.md)                                     | Ensemble          | rmse          |         242098 |         0.38 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

