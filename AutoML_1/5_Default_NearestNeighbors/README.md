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

3.7 seconds

### Metric details
|           |        0 |        1 |   2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|----:|-----------:|------------:|---------------:|----------:|
| precision | 0.75     | 0.75     | 0.5 |   0.666667 |    0.666667 |       0.666667 |  0.527302 |
| recall    | 0.857143 | 0.6      | 0.5 |   0.666667 |    0.652381 |       0.666667 |  0.527302 |
| f1-score  | 0.8      | 0.666667 | 0.5 |   0.666667 |    0.655556 |       0.662963 |  0.527302 |
| support   | 7        | 5        | 6   |   0.666667 |   18        |      18        |  0.527302 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                6 |                0 |                1 |
| Labeled as 1 |                0 |                3 |                2 |
| Labeled as 2 |                2 |                1 |                3 |

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
