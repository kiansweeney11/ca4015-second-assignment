# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model    |   Weight |
|:---------|---------:|
| 2_Linear |        3 |

### Metric details
|           |   EC_A |   EC_B |   PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------:|-------:|-------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |      1 |      1 |      1 |      1 | 0.833333 | 1        |   0.966667 |    0.972222 |       0.972222 |  0.377057 |
| recall    |      1 |      1 |      1 |      1 | 1        | 0.8      |   0.966667 |    0.966667 |       0.966667 |  0.377057 |
| f1-score  |      1 |      1 |      1 |      1 | 0.909091 | 0.888889 |   0.966667 |    0.96633  |       0.96633  |  0.377057 |
| support   |      5 |      5 |      5 |      5 | 5        | 5        |   0.966667 |   30        |      30        |  0.377057 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   5 |                   0 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   0 |                   5 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   1 |                   4 |

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
