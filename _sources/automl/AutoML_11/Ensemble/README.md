# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Default_Xgboost |        1 |

### Metric details
|           |   0 |   1 |   2 |        3 |   4 |        5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|----:|----:|---------:|----:|---------:|-----------:|------------:|---------------:|----------:|
| precision |   1 |   1 |   1 | 0.833333 |   1 | 1        |   0.966667 |    0.972222 |       0.972222 |  0.116492 |
| recall    |   1 |   1 |   1 | 1        |   1 | 0.8      |   0.966667 |    0.966667 |       0.966667 |  0.116492 |
| f1-score  |   1 |   1 |   1 | 0.909091 |   1 | 0.888889 |   0.966667 |    0.96633  |       0.96633  |  0.116492 |
| support   |   5 |   5 |   5 | 5        |   5 | 5        |   0.966667 |   30        |      30        |  0.116492 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                5 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |                5 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                0 |                0 |                5 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |                5 |                0 |                0 |
| Labeled as 4 |                0 |                0 |                0 |                0 |                5 |                0 |
| Labeled as 5 |                0 |                0 |                0 |                1 |                0 |                4 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
