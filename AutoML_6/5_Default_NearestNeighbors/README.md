# Summary of 5_Default_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 5
- **weights**: uniform
- **num_class**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

4.5 seconds

### Metric details
|           |    0 |   1 |        2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----:|----:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 1    | 0.6 | 0.714286 |   0.733333 |    0.771429 |       0.771429 |   2.93421 |
| recall    | 0.6  | 0.6 | 1        |   0.733333 |    0.733333 |       0.733333 |   2.93421 |
| f1-score  | 0.75 | 0.6 | 0.833333 |   0.733333 |    0.727778 |       0.727778 |   2.93421 |
| support   | 5    | 5   | 5        |   0.733333 |   15        |      15        |   2.93421 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                3 |                2 |                0 |
| Labeled as 1 |                0 |                3 |                2 |
| Labeled as 2 |                0 |                0 |                5 |

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
