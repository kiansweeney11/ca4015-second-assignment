# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                                 | Baseline          | rmse          |         434163 |         1.32 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                         | Decision Tree     | rmse          |         497813 |        14.06 |
|              | [3_Linear](3_Linear/README.md)                                     | Linear            | rmse          |         355104 |         8.74 |
|              | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | rmse          |         378897 |         3.79 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | rmse          |         482167 |         1.5  |
| **the best** | [Ensemble](Ensemble/README.md)                                     | Ensemble          | rmse          |         329538 |         0.36 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

