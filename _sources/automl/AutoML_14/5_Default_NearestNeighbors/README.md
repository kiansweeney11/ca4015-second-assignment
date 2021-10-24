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

4.8 seconds

### Metric details
|           |        0 |        1 |        2 |        3 |        4 |   5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|---------:|---------:|----:|-----------:|------------:|---------------:|----------:|
| precision | 0.714286 | 0.666667 | 1        | 0.75     | 0.714286 |   1 |   0.766667 |    0.80754  |       0.80754  |  0.446942 |
| recall    | 1        | 0.8      | 0.2      | 0.6      | 1        |   1 |   0.766667 |    0.766667 |       0.766667 |  0.446942 |
| f1-score  | 0.833333 | 0.727273 | 0.333333 | 0.666667 | 0.833333 |   1 |   0.766667 |    0.732323 |       0.732323 |  0.446942 |
| support   | 5        | 5        | 5        | 5        | 5        |   5 |   0.766667 |   30        |      30        |  0.446942 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                5 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |                4 |                0 |                1 |                0 |                0 |
| Labeled as 2 |                2 |                0 |                1 |                0 |                2 |                0 |
| Labeled as 3 |                0 |                2 |                0 |                3 |                0 |                0 |
| Labeled as 4 |                0 |                0 |                0 |                0 |                5 |                0 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |                5 |

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
