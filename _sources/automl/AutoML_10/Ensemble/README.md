# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                      |   Weight |
|:---------------------------|---------:|
| 2_Linear                   |        2 |
| 5_Default_NearestNeighbors |        3 |

### Metric details
|           |   EC_A |   EC_B |   PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------:|-------:|-------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |      1 |      1 |      1 |      1 | 0.625    | 1        |        0.9 |     0.9375  |        0.9375  |  0.398333 |
| recall    |      1 |      1 |      1 |      1 | 1        | 0.4      |        0.9 |     0.9     |        0.9     |  0.398333 |
| f1-score  |      1 |      1 |      1 |      1 | 0.769231 | 0.571429 |        0.9 |     0.89011 |        0.89011 |  0.398333 |
| support   |      5 |      5 |      5 |      5 | 5        | 5        |        0.9 |    30       |       30       |  0.398333 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   5 |                   0 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   0 |                   5 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   3 |                   2 |

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
