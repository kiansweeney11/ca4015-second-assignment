# Summary of 5_Default_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 5
- **weights**: uniform
- **num_class**: 6
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

7.7 seconds

### Metric details
|           |     EC_A |   EC_B |   PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|-------:|-------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 0.714286 |   1    |      1 |      1 | 0.625    | 1        |   0.833333 |    0.889881 |       0.889881 |  0.788799 |
| recall    | 1        |   0.6  |      1 |      1 | 1        | 0.4      |   0.833333 |    0.833333 |       0.833333 |  0.788799 |
| f1-score  | 0.833333 |   0.75 |      1 |      1 | 0.769231 | 0.571429 |   0.833333 |    0.820665 |       0.820665 |  0.788799 |
| support   | 5        |   5    |      5 |      5 | 5        | 5        |   0.833333 |   30        |      30        |  0.788799 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   5 |                   0 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   2 |                   3 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   0 |                   5 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   3 |                   2 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
