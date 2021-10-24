# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                  |   Weight |
|:-----------------------|---------:|
| 2_Linear               |        1 |
| 4_Default_RandomForest |        4 |

### Metric details
|           |   EC_A |     EC_B |   PA_A |     PA_B |   SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------:|---------:|-------:|---------:|-------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |      0 | 0.416667 |   1    | 0.75     |      0 | 0.454545 |   0.533333 |    0.436869 |       0.436869 |   0.90312 |
| recall    |      0 | 1        |   0.6  | 0.6      |      0 | 1        |   0.533333 |    0.533333 |       0.533333 |   0.90312 |
| f1-score  |      0 | 0.588235 |   0.75 | 0.666667 |      0 | 0.625    |   0.533333 |    0.438317 |       0.438317 |   0.90312 |
| support   |      5 | 5        |   5    | 5        |      5 | 5        |   0.533333 |   30        |      30        |   0.90312 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   3 |                   1 |                   0 |                   1 |
| Labeled as PA_B |                   0 |                   2 |                   0 |                   3 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   0 |                   5 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   0 |                   5 |

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
