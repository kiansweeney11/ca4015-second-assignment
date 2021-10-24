# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                                 | Baseline          | rmse          |         246857 |         1.13 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                         | Decision Tree     | rmse          |         247755 |         5.04 |
|              | [3_Linear](3_Linear/README.md)                                     | Linear            | rmse          |         263535 |         2.75 |
|              | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | rmse          |         239065 |         3.32 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | rmse          |         264148 |         1.83 |
| **the best** | [Ensemble](Ensemble/README.md)                                     | Ensemble          | rmse          |         238931 |         0.41 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

