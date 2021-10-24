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

5.2 seconds

### Metric details
|           |     EC_A |     EC_B |   PA_A |   PA_B |     SA_A |   SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|-------:|-------:|---------:|-------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.227273 |      0 |      0 | 0.5      |      0 |        0.3 |    0.287879 |       0.287879 |   3.42584 |
| recall    | 0.4      | 1        |      0 |      0 | 0.4      |      0 |        0.3 |    0.3      |       0.3      |   3.42584 |
| f1-score  | 0.571429 | 0.37037  |      0 |      0 | 0.444444 |      0 |        0.3 |    0.231041 |       0.231041 |   3.42584 |
| support   | 5        | 5        |      5 |      5 | 5        |      5 |        0.3 |   30        |      30        |   3.42584 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   2 |                   3 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   3 |                   0 |                   0 |                   1 |                   1 |
| Labeled as SA_A |                   0 |                   2 |                   0 |                   0 |                   2 |                   1 |
| Labeled as SA_B |                   0 |                   4 |                   0 |                   0 |                   1 |                   0 |

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
