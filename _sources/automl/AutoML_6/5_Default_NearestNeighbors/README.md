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

5.3 seconds

### Metric details
|           |     EC_A |     EC_B |     PA_A |     PA_B |   SA_A |   SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|---------:|-------:|-------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.666667 | 1        | 1        |   0.25 |      0 |   0.466667 |    0.652778 |       0.652778 |   3.87107 |
| recall    | 0.2      | 0.4      | 0.8      | 0.4      |   1    |      0 |   0.466667 |    0.466667 |       0.466667 |   3.87107 |
| f1-score  | 0.333333 | 0.5      | 0.888889 | 0.571429 |   0.4  |      0 |   0.466667 |    0.448942 |       0.448942 |   3.87107 |
| support   | 5        | 5        | 5        | 5        |   5    |      5 |   0.466667 |   30        |      30        |   3.87107 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   1 |                   1 |                   0 |                   0 |                   3 |                   0 |
| Labeled as EC_B |                   0 |                   2 |                   0 |                   0 |                   3 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   4 |                   0 |                   1 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   0 |                   2 |                   3 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |

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
