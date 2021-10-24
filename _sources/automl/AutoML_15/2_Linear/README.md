# Summary of 2_Linear

[<< Go back](../README.md)


## Logistic Regression (Linear)
- **n_jobs**: -1
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

20.2 seconds

### Metric details
|           |        0 |   1 |        2 |    3 |   4 |   5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|----:|---------:|-----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision | 0.625    |   1 | 1        | 1    |   1 |   1 |        0.9 |    0.9375   |       0.9375   |  0.330437 |
| recall    | 1        |   1 | 0.8      | 0.6  |   1 |   1 |        0.9 |    0.9      |       0.9      |  0.330437 |
| f1-score  | 0.769231 |   1 | 0.888889 | 0.75 |   1 |   1 |        0.9 |    0.901353 |       0.901353 |  0.330437 |
| support   | 5        |   5 | 5        | 5    |   5 |   5 |        0.9 |   30        |      30        |  0.330437 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                5 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |                5 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                1 |                0 |                4 |                0 |                0 |                0 |
| Labeled as 3 |                2 |                0 |                0 |                3 |                0 |                0 |
| Labeled as 4 |                0 |                0 |                0 |                0 |                5 |                0 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |                5 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |           0 |           1 |            2 |           3 |           4 |            5 |
|:----------------------------------------------|------------:|------------:|-------------:|------------:|------------:|-------------:|
| intercept                                     |  0.339413   |  0.758309   | -0.252092    | -0.363753   | -0.143017   | -0.338859    |
| Ethyl Acetate                                 |  0.143964   | -0.363141   |  0.370568    | -0.188988   |  0.0896592  | -0.052062    |
| Ethanol                                       | -0.251278   |  0.0846128  |  0.362106    | -0.16775    |  0.0016583  | -0.0293482   |
| Propanoic acid, ethyl ester                   |  0.156757   |  0.118373   | -0.0639485   |  0.0612147  | -0.338813   |  0.0664165   |
| 2-Pentanone                                   |  0.146192   | -0.230076   |  0.135334    | -0.0415355  |  0.0215997  | -0.0315137   |
| Decane                                        | -0.320206   |  0.303991   | -0.0231894   |  0.172821   | -0.179435   |  0.0460195   |
| Methyl Isobutyl Ketone                        | -0.414156   |  0.646808   |  0.00343241  | -0.0434948  |  0.0542996  | -0.246889    |
| Amylene hydrate                               | -0.58138    |  0.434368   |  0.135136    |  0.217258   | -0.0164694  | -0.188913    |
| Butanoic acid, 2-methyl-, methyl ester        |  0.096645   | -0.00462368 | -0.0387068   | -0.19842    | -0.0122323  |  0.157338    |
| Isobutyl acetate                              |  0.0491971  | -0.0265683  |  0.249714    | -0.196432   | -0.163692   |  0.087782    |
| Methyl isovalerate                            | -0.428289   | -0.502843   |  0.105079    |  0.119418   |  0.07044    |  0.636195    |
| 1-Propanol                                    |  0.0337241  | -0.0466039  |  0.385781    | -0.00343501 | -0.403311   |  0.0338448   |
| Methyl thiolacetate                           | -0.88109    |  0.841914   | -0.0727387   |  0.238574   | -0.2747     |  0.148041    |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.244696   |  0.0981011  |  0.0789348   |  0.00441559 | -0.0128358  |  0.0760801   |
| 2-Hexanone                                    | -0.56129    | -0.349574   |  0.197408    |  0.113163   |  0.453891   |  0.146402    |
| Ethyl isocyanide                              |  0.1194     |  0.02296    | -0.161977    |  0.019161   | -0.0269717  |  0.0274272   |
| 1-Propanol, 2-methyl-                         | -0.0834775  |  0.276855   | -0.050845    |  0.181789   | -0.116868   | -0.207454    |
| 2-Pentanol, 2-methyl-                         |  0.169532   | -0.36411    | -0.0456703   |  0.384928   |  0.0691435  | -0.213824    |
| 2-Pentanol                                    | -0.2402     | -0.726094   |  0.16884     |  0.427727   |  0.161912   |  0.207815    |
| 1-Butanol, 3-methyl-, acetate                 |  0.0897006  | -0.151055   |  8.74253e-06 |  0.0308654  |  0.0696392  | -0.0391591   |
| 1 - Undecene                                  | -0.0870249  |  0.0178387  | -0.00300224  | -0.369673   |  0.00754379 |  0.434318    |
| 1-Butanol                                     |  0.0416228  |  0.0647804  |  0.0737569   | -0.0469589  | -0.007262   | -0.125939    |
| 2-Heptanone                                   | -0.224818   | -0.420496   |  0.423741    | -0.00677766 |  0.306335   | -0.0779844   |
| Dodecane                                      |  0.0884118  | -0.085079   | -0.133383    |  0.408616   | -0.142395   | -0.136171    |
| 1-Butanol, 3-methyl-                          | -0.60122    |  0.0803039  | -0.117397    |  0.427851   | -0.0731971  |  0.28366     |
| S-Methyl 3-methylbutanethioate                |  0.0575032  |  0.00798871 |  0.0285616   |  0.0152844  |  0.0416887  | -0.151027    |
| 2-Heptanone, 4,6-dimethyl-                    |  0.20774    |  0.0308132  | -0.0413802   |  0.131989   | -0.122611   | -0.206551    |
| 3-Buten-1-ol, 3-methyl-                       |  0.246511   | -0.196492   | -0.129794    | -0.147842   | -0.0607252  |  0.288342    |
| Thiocyanic acid, methyl ester                 |  0.145585   |  0.132608   | -0.00273427  | -0.37941    |  0.0381186  |  0.0658334   |
| Acetoin                                       |  0.422183   |  0.195838   | -0.146502    | -0.16655    | -0.192143   | -0.112827    |
| 1-Pentanol, 2-methyl-                         |  0.160736   |  0.0531096  |  0.0242539   |  0.0204338  | -0.324373   |  0.0658399   |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester |  0.0385007  | -0.0909096  |  0.0122207   |  0.175564   | -0.0108893  | -0.124486    |
| 2-Heptanol, 4-methyl-                         |  0.0698241  | -0.0527402  |  0.0221523   |  0.108209   |  0.0285557  | -0.176001    |
| 2-Nonanone                                    | -0.0551468  |  0.0386132  | -0.36206     | -0.187953   |  0.131783   |  0.434764    |
| Acetic acid                                   |  0.109415   |  0.214299   | -0.391202    | -0.0579475  |  0.130221   | -0.00478604  |
| 2-Nonanol                                     | -0.117397   |  0.00635298 |  0.0254749   | -0.163565   | -0.0193783  |  0.268513    |
| Pyrrole                                       | -0.0829741  | -0.0645607  | -0.0428138   |  0.53062    | -0.0666745  | -0.273597    |
| 1H-Pyrrole, 2-methyl-                         | -0.102464   | -0.0412458  |  0.00612705  |  0.24466    | -0.0305773  | -0.0765004   |
| 1-Heptanol, 2,4-dimethyl-,                    | -0.0124292  |  0.0698405  |  0.388029    | -0.296858   |  0.0669071  | -0.215489    |
| Propanoic acid                                | -0.916047   |  0.686356   | -0.0170434   | -0.0417028  |  0.306819   | -0.018383    |
| Propanoic acid, 2-methyl-                     | -0.0287634  | -0.0279003  |  0.0490731   | -0.0505605  |  0.0538968  |  0.00425429  |
| 1-Octanol                                     |  0.01499    |  0.0959756  |  0.00982507  |  0.0382558  | -0.163498   |  0.00445146  |
| 2-Undecanone                                  |  0.102998   |  0.0899463  | -0.344218    | -0.212339   | -0.120388   |  0.484       |
| Benzoic acid, methyl ester                    |  0.0332231  |  0.163054   |  0.296672    | -0.240637   |  0.122321   | -0.374633    |
| Butyrolactone                                 |  0.192027   | -0.260486   |  0.0294042   | -0.0148667  |  0.0312892  |  0.022632    |
| Decanoic acid, ethyl ester                    |  0.0148498  |  0.00544933 | -0.0442333   |  0.0218422  | -0.00375569 |  0.0058476   |
| Acetic acid, decyl ester                      |  0.0435227  |  0.0178168  | -0.130222    |  0.0261433  |  0.0380886  |  0.00465085  |
| 2-Undecanol                                   |  0.0935609  |  0.085495   | -0.317055    |  0.136599   | -0.15273    |  0.154131    |
| Butanoic acid, 3-methyl-                      |  0.459492   | -0.391908   |  0.0208059   | -0.0411201  | -0.0899212  |  0.0426519   |
| 2-Dodecanone                                  |  0.0661833  | -0.0196657  |  0.0532362   | -0.0146338  | -0.13108    |  0.0459597   |
| 1-Decanol                                     |  0.0387178  |  0.0408922  | -0.249522    |  0.0238235  |  0.153376   | -0.0072879   |
| 2-Tridecanone                                 |  0.0783913  | -0.00795962 |  0.081889    |  0.0022077  | -0.196764   |  0.042236    |
| Dodecanoic acid, ethyl ester                  |  0.00844367 |  0.00534164 | -0.0662558   |  0.0239687  |  0.0182486  |  0.0102532   |
| 1,4-Butanediol                                |  0.103061   | -0.230528   |  0.0448517   | -0.00253798 |  0.0449638  |  0.0401895   |
| Phenylethyl Alcohol                           |  0.0228695  |  0.137484   | -0.120112    |  0.0277087  | -0.0954571  |  0.0275077   |
| Acetophenone, 2'-amino-                       | -0.00759991 | -0.00921006 |  0.0140386   | -0.319073   |  0.0151137  |  0.306731    |
| 2-Tridecanol                                  |  0.0440812  | -0.00582156 | -0.429767    | -0.00408515 |  0.396164   | -0.000571595 |
| Tetradecanal                                  | -0.0144645  |  0.0344382  |  0.118799    |  0.0279669  | -0.19719    |  0.0304504   |
| 1-Dodecanol                                   |  0.0473658  |  0.0454976  |  0.088208    |  0.0286976  | -0.228486   |  0.0187169   |
| Methyl tetradecanoate                         |  0.0736     | -0.0801811  | -0.324631    | -0.00496824 |  0.344378   | -0.00819726  |
| 2-Pentadecanone                               |  0.115162   | -0.0757708  | -0.143284    |  0.00228106 |  0.0828591  |  0.0187519   |
| Tetradecanoic acid, ethyl ester               | -0.0262565  | -0.00859686 |  0.0400432   |  0.0222177  | -0.0384758  |  0.0110682   |
| Hexadecanal                                   |  0.0387251  |  0.0600122  |  0.167929    |  0.0440201  | -0.346374   |  0.0356873   |
| n-Tridecan-1-ol                               |  0.091234   | -0.0655073  | -0.0872478   | -0.0221663  |  0.0464544  |  0.037233    |
| 1-Tetradecanol                                |  0.0626052  |  0.0996561  |  0.469837    |  0.0488006  | -0.732386   |  0.0514865   |
| n-Pentadecanol                                |  0.041289   | -0.00207317 |  0.203282    |  0.00694343 | -0.260443   |  0.0110026   |
| 1-Hexadecanol                                 |  0.10126    | -0.0524881  |  0.242502    |  0.0288378  | -0.340708   |  0.0205961   |
| Indole                                        | -0.26361    |  0.0741732  |  0.336105    | -0.0144043  | -0.11219    | -0.0200738   |


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

### Dependence 0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.png)
### Dependence 1 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_1.png)
### Dependence 2 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_2.png)
### Dependence 3 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_3.png)
### Dependence 4 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_4.png)
### Dependence 5 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_5.png)

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
