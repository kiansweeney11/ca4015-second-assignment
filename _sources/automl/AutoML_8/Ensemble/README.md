# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model    |   Weight |
|:---------|---------:|
| 2_Linear |        1 |

### Metric details
|           |     EC_A |     EC_B |     PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.833333 | 0.5      |      0 | 0.833333 | 1        |   0.766667 |    0.694444 |       0.694444 |  0.666864 |
| recall    | 0.8      | 1        | 1        |      0 | 1        | 0.8      |   0.766667 |    0.766667 |       0.766667 |  0.666864 |
| f1-score  | 0.888889 | 0.909091 | 0.666667 |      0 | 0.909091 | 0.888889 |   0.766667 |    0.710438 |       0.710438 |  0.666864 |
| support   | 5        | 5        | 5        |      5 | 5        | 5        |   0.766667 |   30        |      30        |  0.666864 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   4 |                   1 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
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