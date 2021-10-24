# Summary of 4_Default_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 4
- **eval_metric_name**: logloss
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

21.8 seconds

### Metric details
|           |   EC_A |     EC_B |     PA_A |     PA_B |   SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------:|---------:|---------:|---------:|-------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |      0 | 0.444444 | 0.25     | 0.5      |      0 | 0.454545 |   0.433333 |    0.274832 |       0.274832 |  0.912605 |
| recall    |      0 | 0.8      | 0.2      | 0.6      |      0 | 1        |   0.433333 |    0.433333 |       0.433333 |  0.912605 |
| f1-score  |      0 | 0.571429 | 0.222222 | 0.545455 |      0 | 0.625    |   0.433333 |    0.327351 |       0.327351 |  0.912605 |
| support   |      5 | 5        | 5        | 5        |      5 | 5        |   0.433333 |   30        |      30        |  0.912605 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   4 |                   1 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   1 |                   3 |                   0 |                   1 |
| Labeled as PA_B |                   0 |                   0 |                   2 |                   3 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   0 |                   5 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   0 |                   5 |

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
