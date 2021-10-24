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
|           |        0 |        1 |   2 |   3 |        4 |        5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|----:|----:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 0.5      | 0.75     | 0.8 |   1 | 0.75     | 1        |   0.766667 |    0.8      |       0.8      |   1.25245 |
| recall    | 0.8      | 0.6      | 0.8 |   1 | 0.6      | 0.8      |   0.766667 |    0.766667 |       0.766667 |   1.25245 |
| f1-score  | 0.615385 | 0.666667 | 0.8 |   1 | 0.666667 | 0.888889 |   0.766667 |    0.772934 |       0.772934 |   1.25245 |
| support   | 5        | 5        | 5   |   5 | 5        | 5        |   0.766667 |   30        |      30        |   1.25245 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                4 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                2 |                3 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                0 |                0 |                4 |                0 |                1 |                0 |
| Labeled as 3 |                0 |                0 |                0 |                5 |                0 |                0 |
| Labeled as 4 |                1 |                0 |                1 |                0 |                3 |                0 |
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
