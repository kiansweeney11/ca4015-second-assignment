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

21.3 seconds

### Metric details
|           |   0 |   1 |   2 |   3 |   4 |   5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|----:|----:|----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 |  0.152763 |
| recall    |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 |  0.152763 |
| f1-score  |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 |  0.152763 |
| support   |   5 |   5 |   5 |   5 |   5 |   5 |          1 |          30 |             30 |  0.152763 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                5 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |                5 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                0 |                0 |                5 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |                5 |                0 |                0 |
| Labeled as 4 |                0 |                0 |                0 |                0 |                5 |                0 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |                5 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |           0 |           1 |           2 |           3 |           4 |            5 |
|:----------------------------------------------|------------:|------------:|------------:|------------:|------------:|-------------:|
| intercept                                     |  0.288113   |  0.857632   | -0.261296   | -0.0555697  | -0.456922   | -0.371957    |
| Ethyl Acetate                                 |  0.0350443  | -0.329196   |  0.365125   | -0.233461   |  0.159358   |  0.00313039  |
| Ethanol                                       | -0.186596   |  0.127519   |  0.400863   | -0.224518   | -0.0658742  | -0.0513936   |
| Propanoic acid, ethyl ester                   |  0.0705288  |  0.075609   |  0.011445   |  0.0544638  | -0.246303   |  0.034256    |
| 2-Pentanone                                   |  0.13012    | -0.245921   |  0.141533   | -0.103173   |  0.0823692  | -0.00492872  |
| Decane                                        | -0.480513   |  0.271681   | -0.0686532  |  0.417238   | -0.170912   |  0.0311598   |
| Methyl Isobutyl Ketone                        | -0.320717   |  0.63583    | -0.0271723  | -0.135301   |  0.00123594 | -0.153875    |
| Amylene hydrate                               | -0.683878   |  0.552959   |  0.118694   |  0.0410138  |  0.131809   | -0.160597    |
| Butanoic acid, 2-methyl-, methyl ester        |  0.0730348  |  0.031636   | -0.0296307  | -0.194233   |  0.00387308 |  0.11532     |
| Isobutyl acetate                              |  0.0834717  |  0.0138948  |  0.127828   | -0.31551    |  0.033678   |  0.0566379   |
| Methyl isovalerate                            | -0.371732   | -0.576002   |  0.0840126  |  0.299496   |  0.053569   |  0.510656    |
| 1-Propanol                                    | -0.0105011  | -0.0440151  |  0.417108   | -0.0399076  | -0.347187   |  0.0245028   |
| Methyl thiolacetate                           | -0.751594   |  0.707876   | -0.102884   |  0.223413   | -0.295119   |  0.218309    |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.076963   | -0.00711294 |  0.0403155  |  0.040532   | -0.039644   |  0.0428724   |
| 2-Hexanone                                    | -0.559811   | -0.501785   |  0.168397   |  0.248607   |  0.515302   |  0.12929     |
| Ethyl isocyanide                              |  0.100707   |  0.0181408  | -0.026469   |  0.0572536  | -0.156036   |  0.00640372  |
| 1-Propanol, 2-methyl-                         | -0.166484   |  0.316285   | -0.106828   |  0.0726002  | -0.0610379  | -0.0545352   |
| 2-Pentanol, 2-methyl-                         |  0.106628   | -0.303829   | -0.00957141 |  0.232121   |  0.0402309  | -0.0655797   |
| 2-Pentanol                                    | -0.202123   | -0.679966   |  0.109938   |  0.45097    |  0.0865143  |  0.234667    |
| 1-Butanol, 3-methyl-, acetate                 | -0.0934147  |  0.0157028  |  0.0125069  |  0.0296669  |  0.0673074  | -0.0317694   |
| 1 - Undecene                                  |  0.016073   |  0.0851167  |  0.0167507  | -0.621345   |  0.0190167  |  0.484387    |
| 1-Butanol                                     |  0.0724174  |  0.0714775  |  0.0531323  |  0.0614569  |  0.0204108  | -0.278895    |
| 2-Heptanone                                   | -0.195584   | -0.45269    |  0.431764   | -0.0395051  |  0.27382    | -0.0178048   |
| Dodecane                                      |  0.0504651  |  0.0310626  | -0.0330222  |  0.284135   | -0.144      | -0.18864     |
| 1-Butanol, 3-methyl-                          | -0.525787   |  0.0288898  | -0.0856624  |  0.398705   | -0.0535127  |  0.237367    |
| S-Methyl 3-methylbutanethioate                |  0.125806   |  0.0284045  |  0.00133408 |  0.0816364  |  0.02171    | -0.258891    |
| 2-Heptanone, 4,6-dimethyl-                    |  0.223605   |  0.0283248  | -0.115546   | -0.0302036  | -0.0737867  | -0.0323936   |
| 3-Buten-1-ol, 3-methyl-                       |  0.208511   | -0.19916    | -0.0693307  | -0.312147   |  0.00343661 |  0.36869     |
| Thiocyanic acid, methyl ester                 |  0.102902   |  0.115372   |  0.00957676 | -0.58298    |  0.023836   |  0.331293    |
| Acetoin                                       |  0.519447   |  0.124535   | -0.14277    | -0.214074   | -0.143491   | -0.143646    |
| 1-Pentanol, 2-methyl-                         |  0.172854   |  0.0572772  |  0.00136318 |  0.117657   | -0.400903   |  0.0517515   |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester |  0.0839605  | -0.0468345  |  0.0285806  | -0.075011   |  0.0137844  | -0.00448003  |
| 2-Heptanol, 4-methyl-                         |  0.0857398  | -0.0818377  |  0.0172019  |  0.0670752  |  0.0246022  | -0.112781    |
| 2-Nonanone                                    | -0.0300736  |  0.107296   | -0.417286   | -0.182682   |  0.14821    |  0.374536    |
| Acetic acid                                   |  0.0110976  |  0.295152   | -0.364949   | -0.0544015  |  0.124441   | -0.0113409   |
| 2-Nonanol                                     | -0.0731464  |  0.00253711 |  0.0420486  | -0.20903    | -0.0169616  |  0.254553    |
| Pyrrole                                       |  0.0200952  |  0.0723187  |  0.033571   |  0.237441   |  0.0138302  | -0.377256    |
| 1H-Pyrrole, 2-methyl-                         |  0.0132046  |  0.0142589  |  0.0396251  | -0.110279   |  0.00337617 |  0.0398142   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.0507945  |  0.107386   |  0.338619   | -0.448413   |  0.183362   | -0.231749    |
| Propanoic acid                                | -1.03919    |  0.784974   |  0.0162404  | -0.0691088  |  0.311028   | -0.00393848  |
| Propanoic acid, 2-methyl-                     | -0.0677122  | -0.00153686 |  0.0576185  | -0.0437558  |  0.0481797  |  0.00720666  |
| 1-Octanol                                     | -0.0170018  |  0.10358    | -0.0387186  |  0.0503441  | -0.0833696  | -0.0148343   |
| 2-Undecanone                                  |  0.133047   |  0.111087   | -0.247513   | -0.346681   | -0.136821   |  0.486881    |
| Benzoic acid, methyl ester                    |  0.114597   |  0.205423   |  0.245617   | -0.372299   |  0.146386   | -0.339723    |
| Butyrolactone                                 |  0.0508796  | -0.167273   |  0.0401848  |  0.0015678  |  0.0416198  |  0.0330214   |
| Decanoic acid, ethyl ester                    |  0.0274862  |  0.0125352  | -0.0063828  |  0.0257827  | -0.0705292  |  0.0111079   |
| Acetic acid, decyl ester                      |  0.0532965  |  0.00501816 | -0.122334   |  0.0364169  |  0.0275512  |  5.09512e-05 |
| 2-Undecanol                                   |  0.0763378  | -0.0375073  | -0.176942   |  0.00215282 | -0.105698   |  0.241657    |
| Butanoic acid, 3-methyl-                      |  0.584949   | -0.499862   | -0.00174906 | -0.00557701 | -0.0989042  |  0.0211429   |
| 2-Dodecanone                                  |  0.1032     |  0.0103834  |  0.0547877  |  0.0143691  | -0.232301   |  0.0495603   |
| 1-Decanol                                     |  0.0356633  |  0.0327159  | -0.276034   |  0.0343966  |  0.190463   | -0.0172048   |
| 2-Tridecanone                                 |  0.116774   |  0.00779512 |  0.0506496  |  0.0340369  | -0.246691   |  0.0374363   |
| Dodecanoic acid, ethyl ester                  |  0.0328421  |  0.0139751  | -0.0526981  |  0.0325145  | -0.0416459  |  0.0150123   |
| 1,4-Butanediol                                | -0.0410313  | -0.122182   |  0.0523172  |  0.0165219  |  0.0489283  |  0.045446    |
| Phenylethyl Alcohol                           |  0.0536849  |  0.155319   | -0.143035   |  0.102233   | -0.1748     |  0.00659807  |
| Acetophenone, 2'-amino-                       |  0.0252581  |  0.00101154 |  0.0234831  | -0.358191   |  0.0244546  |  0.283984    |
| 2-Tridecanol                                  |  0.12209    |  0.0229914  | -0.521896   |  0.0661009  |  0.304918   |  0.00579561  |
| Tetradecanal                                  |  0.00769671 |  0.0448819  |  0.0464989  |  0.0435109  | -0.166153   |  0.0235641   |
| 1-Dodecanol                                   |  0.0154653  |  0.0311131  | -0.0120079  |  0.029476   | -0.0691586  |  0.00511209  |
| Methyl tetradecanoate                         |  0.12516    | -0.0943797  | -0.329302   |  0.0125615  |  0.288498   | -0.00253753  |
| 2-Pentadecanone                               |  0.162313   | -0.0686526  | -0.124967   |  0.0139577  | -0.00677586 |  0.0241245   |
| Tetradecanoic acid, ethyl ester               |  0.0235443  |  0.0241284  | -0.0153814  |  0.0437972  | -0.0937471  |  0.0176586   |
| Hexadecanal                                   | -0.0233599  |  0.0196735  |  0.274646   | -0.0148251  | -0.269238   |  0.0131032   |
| n-Tridecan-1-ol                               |  0.18484    | -0.0183559  | -0.167742   |  0.0351868  | -0.0874544  |  0.0535255   |
| 1-Tetradecanol                                |  0.0252406  |  0.0964244  |  0.463845   |  0.0450309  | -0.661484   |  0.0309425   |
| n-Pentadecanol                                | -0.0156615  | -0.0335003  |  0.299712   | -0.0781196  | -0.16791    | -0.00452051  |
| 1-Hexadecanol                                 |  0.0521231  | -0.100836   |  0.300075   | -0.0326405  | -0.225289   |  0.00656658  |
| Indole                                        | -0.107593   |  0.0998742  |  0.403071   |  0.0114733  | -0.392756   | -0.014069    |


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
