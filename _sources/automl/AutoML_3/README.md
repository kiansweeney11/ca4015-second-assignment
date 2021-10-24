# AutoML Leaderboard

| Best model   | name                                                               | model_type        | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:------------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                                 | Baseline          | rmse          |         229606 |         1.42 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                         | Decision Tree     | rmse          |         491324 |         4.68 |
|              | [3_Linear](3_Linear/README.md)                                     | Linear            | rmse          |         778165 |         3.18 |
|              | [4_Default_RandomForest](4_Default_RandomForest/README.md)         | Random Forest     | rmse          |         175504 |         3.05 |
|              | [5_Default_NearestNeighbors](5_Default_NearestNeighbors/README.md) | Nearest Neighbors | rmse          |         188088 |         1.74 |
| **the best** | [Ensemble](Ensemble/README.md)                                     | Ensemble          | rmse          |         173854 |         0.33 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

