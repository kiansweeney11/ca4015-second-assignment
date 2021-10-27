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

4.4 seconds

### Metric details
|           |   0 |        1 |        2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |   1 | 1        | 0.666667 |     0.8125 |    0.888889 |       0.875    |  0.509122 |
| recall    |   1 | 0.4      | 1        |     0.8125 |    0.8      |       0.8125   |  0.509122 |
| f1-score  |   1 | 0.571429 | 0.8      |     0.8125 |    0.790476 |       0.791071 |  0.509122 |
| support   |   5 | 5        | 6        |     0.8125 |   16        |      16        |  0.509122 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                5 |                0 |                0 |
| Labeled as 1 |                0 |                2 |                3 |
| Labeled as 2 |                0 |                0 |                6 |

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
