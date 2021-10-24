# Summary of 3_Default_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.075
- **max_depth**: 6
- **min_child_weight**: 1
- **subsample**: 1.0
- **colsample_bytree**: 1.0
- **eval_metric**: mlogloss
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

28.7 seconds

### Metric details
|           |     EC_A |     EC_B |     PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.277778 | 0.5      |      0 | 0.5      | 1        |   0.433333 |    0.546296 |       0.546296 |   1.33691 |
| recall    | 0.4      | 1        | 0.6      |      0 | 0.2      | 0.4      |   0.433333 |    0.433333 |       0.433333 |   1.33691 |
| f1-score  | 0.571429 | 0.434783 | 0.545455 |      0 | 0.285714 | 0.571429 |   0.433333 |    0.401468 |       0.401468 |   1.33691 |
| support   | 5        | 5        | 5        |      5 | 5        | 5        |   0.433333 |   30        |      30        |   1.33691 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   2 |                   3 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   1 |                   3 |                   0 |                   1 |                   0 |
| Labeled as PA_B |                   0 |                   2 |                   3 |                   0 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   4 |                   0 |                   0 |                   1 |                   0 |
| Labeled as SA_B |                   0 |                   3 |                   0 |                   0 |                   0 |                   2 |

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



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots


## SHAP Decision plots

### Worst decisions for selected sample 1 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_0_worst_decisions.png)
### Worst decisions for selected sample 2 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_1_worst_decisions.png)
### Worst decisions for selected sample 3 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_2_worst_decisions.png)
### Worst decisions for selected sample 4 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_3_worst_decisions.png)
### Best decisions for selected sample 1 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_0_best_decisions.png)
### Best decisions for selected sample 2 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_1_best_decisions.png)
### Best decisions for selected sample 3 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_2_best_decisions.png)
### Best decisions for selected sample 4 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_3_best_decisions.png)

[<< Go back](../README.md)
