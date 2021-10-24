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

4.5 seconds

### Metric details
|           |        0 |        1 |        2 |        3 |        4 |        5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|---------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 0.5      | 0.5      | 0.833333 | 1        | 1        | 1        |   0.733333 |    0.805556 |       0.805556 |   1.33566 |
| recall    | 0.4      | 1        | 1        | 0.4      | 0.8      | 0.8      |   0.733333 |    0.733333 |       0.733333 |   1.33566 |
| f1-score  | 0.444444 | 0.666667 | 0.909091 | 0.571429 | 0.888889 | 0.888889 |   0.733333 |    0.728235 |       0.728235 |   1.33566 |
| support   | 5        | 5        | 5        | 5        | 5        | 5        |   0.733333 |   30        |      30        |   1.33566 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                2 |                3 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |                5 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                0 |                0 |                5 |                0 |                0 |                0 |
| Labeled as 3 |                1 |                2 |                0 |                2 |                0 |                0 |
| Labeled as 4 |                0 |                0 |                1 |                0 |                4 |                0 |
| Labeled as 5 |                1 |                0 |                0 |                0 |                0 |                4 |

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
