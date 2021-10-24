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

20.6 seconds

### Metric details
|           |   0 |   1 |   2 |   3 |   4 |   5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|----:|----:|----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0940139 |
| recall    |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0940139 |
| f1-score  |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0940139 |
| support   |   5 |   5 |   5 |   5 |   5 |   5 |          1 |          30 |             30 | 0.0940139 |


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
|                                               |            0 |           1 |           2 |           3 |           4 |            5 |
|:----------------------------------------------|-------------:|------------:|------------:|------------:|------------:|-------------:|
| intercept                                     |  0.359875    |  0.619081   | -0.202665   | -0.207658   | -0.263494   | -0.305138    |
| Ethyl Acetate                                 |  0.059353    | -0.3179     |  0.482615   | -0.196464   |  0.0151252  | -0.0427286   |
| Ethanol                                       | -0.297075    |  0.148199   |  0.409982   | -0.237609   |  0.00322674 | -0.0267237   |
| Propanoic acid, ethyl ester                   |  0.143516    |  0.0950831  | -0.0646912  |  0.0819738  | -0.317265   |  0.0613838   |
| 2-Pentanone                                   |  0.197144    | -0.303738   |  0.133179   | -0.0265183  |  0.022552   | -0.022619    |
| Decane                                        | -0.230873    |  0.129613   | -0.0337119  |  0.244223   | -0.163177   |  0.0539264   |
| Methyl Isobutyl Ketone                        | -0.417873    |  0.535821   |  0.0300208  | -0.0140617  |  0.0856699  | -0.219577    |
| Amylene hydrate                               | -0.360668    |  0.271216   |  0.076625   |  0.15137    |  0.0301603  | -0.168703    |
| Butanoic acid, 2-methyl-, methyl ester        |  0.161473    |  0.0577379  | -0.0373594  | -0.369543   |  0.002761   |  0.18493     |
| Isobutyl acetate                              |  0.0790821   |  0.00936977 |  0.229475   | -0.262792   | -0.176192   |  0.121058    |
| Methyl isovalerate                            | -0.462652    | -0.401519   |  0.135081   | -0.00421641 |  0.0683388  |  0.664968    |
| 1-Propanol                                    |  0.0257026   | -0.0355318  |  0.447127   | -0.00655892 | -0.465226   |  0.034488    |
| Methyl thiolacetate                           | -0.836053    |  0.924418   | -0.157741   |  0.19028    | -0.248249   |  0.127345    |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.301211    |  0.193774   |  0.0494906  |  0.0310748  | -0.022748   |  0.0496195   |
| 2-Hexanone                                    | -0.593422    | -0.48372    |  0.111548   |  0.244396   |  0.535525   |  0.185674    |
| Ethyl isocyanide                              |  0.0770199   |  0.00765749 | -0.132541   |  0.0588798  | -0.033671   |  0.0226543   |
| 1-Propanol, 2-methyl-                         | -0.201346    |  0.513272   | -0.116644   |  0.144795   | -0.126411   | -0.213665    |
| 2-Pentanol, 2-methyl-                         |  0.22131     | -0.333009   | -0.0566624  |  0.250838   |  0.0747576  | -0.157235    |
| 2-Pentanol                                    | -0.293052    | -0.59868    |  0.155907   |  0.458444   |  0.104135   |  0.173244    |
| 1-Butanol, 3-methyl-, acetate                 |  0.0442464   | -0.0271358  | -0.0238552  |  0.00519123 |  0.0442817  | -0.0427284   |
| 1 - Undecene                                  | -0.0251072   |  0.0852616  |  0.0219857  | -0.562628   |  0.0424454  |  0.438042    |
| 1-Butanol                                     |  0.116077    |  0.120565   |  0.0836714  | -0.233809   |  0.011236   | -0.0977405   |
| 2-Heptanone                                   | -0.256547    | -0.341636   |  0.35497    | -0.0239385  |  0.3586     | -0.0914491   |
| Dodecane                                      |  0.0728871   | -0.045672   | -0.0300744  |  0.378913   | -0.169258   | -0.206795    |
| 1-Butanol, 3-methyl-                          | -0.574585    |  0.112782   | -0.0905943  |  0.341758   | -0.0764239  |  0.287062    |
| S-Methyl 3-methylbutanethioate                |  0.140967    | -0.0148687  |  0.0305226  | -0.104553   |  0.0594052  | -0.111473    |
| 2-Heptanone, 4,6-dimethyl-                    |  0.236319    |  0.0530389  | -0.057229   |  0.11648    | -0.131105   | -0.217504    |
| 3-Buten-1-ol, 3-methyl-                       |  0.273802    | -0.165164   | -0.127513   | -0.196605   | -0.0723573  |  0.287837    |
| Thiocyanic acid, methyl ester                 |  0.214577    |  0.156428   |  0.00172569 | -0.499712   |  0.058075   |  0.0689066   |
| Acetoin                                       |  0.30379     |  0.199727   |  0.0727394  | -0.173715   | -0.274983   | -0.127559    |
| 1-Pentanol, 2-methyl-                         |  0.237449    |  0.0867375  | -0.218204   |  0.122347   | -0.325695   |  0.0973648   |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester |  0.13012     | -0.0568449  |  0.0321752  | -0.0400315  |  0.0282679  | -0.093687    |
| 2-Heptanol, 4-methyl-                         |  0.0998531   | -0.119612   |  0.0180945  |  0.11894    |  0.0274799  | -0.144755    |
| 2-Nonanone                                    | -0.0270687   |  0.0227672  | -0.409653   | -0.140554   |  0.126511   |  0.427998    |
| Acetic acid                                   |  0.106584    |  0.197176   | -0.386027   | -0.0367215  |  0.129469   | -0.0104803   |
| 2-Nonanol                                     | -0.090042    | -0.0142773  |  0.0317145  | -0.1756     | -0.0114464  |  0.259651    |
| Pyrrole                                       |  0.0813982   |  0.0641335  | -0.0120563  |  0.0997906  |  0.00585546 | -0.239121    |
| 1H-Pyrrole, 2-methyl-                         |  0.0381362   |  0.00122228 |  0.0377338  | -0.0648637  |  0.0313116  | -0.0435401   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.113122    |  0.13162    |  0.212996   | -0.367875   |  0.161426   | -0.251288    |
| Propanoic acid                                | -0.870267    |  0.643509   |  0.00311259 | -0.0529148  |  0.2999     | -0.0233404   |
| Propanoic acid, 2-methyl-                     | -0.0823801   |  0.0731142  |  0.0457488  | -0.0618254  |  0.0297018  | -0.00435925  |
| 1-Octanol                                     |  0.000246381 |  0.0839154  |  0.0232905  |  0.0707261  | -0.190152   |  0.0119732   |
| 2-Undecanone                                  |  0.142675    |  0.131355   | -0.37669    | -0.299147   | -0.103367   |  0.505174    |
| Benzoic acid, methyl ester                    |  0.0870761   |  0.170954   |  0.263753   | -0.280187   |  0.128087   | -0.369683    |
| Butyrolactone                                 |  0.119522    | -0.15416    |  0.0425178  | -0.0345861  |  0.0139418  |  0.0127645   |
| Decanoic acid, ethyl ester                    |  0.017683    | -0.00250503 | -0.057153   |  0.0327151  |  0.00372159 |  0.00553828  |
| Acetic acid, decyl ester                      |  0.0357553   |  0.0109087  | -0.129536   |  0.0406049  |  0.0428856  | -0.000618581 |
| 2-Undecanol                                   |  0.173544    |  0.0861127  | -0.396699   |  0.0688292  | -0.111402   |  0.179616    |
| Butanoic acid, 3-methyl-                      |  0.452522    | -0.332995   | -0.0182853  | -0.031573   | -0.0947743  |  0.0251056   |
| 2-Dodecanone                                  |  0.0356704   | -0.00908415 |  0.0818886  | -0.0122916  | -0.139752   |  0.0435691   |
| 1-Decanol                                     |  0.036867    |  0.0307616  | -0.224152   |  0.0404395  |  0.128163   | -0.0120788   |
| 2-Tridecanone                                 |  0.0894955   |  0.00754985 |  0.0322462  |  0.0291849  | -0.201578   |  0.0431017   |
| Dodecanoic acid, ethyl ester                  | -0.00255064  | -0.00225415 | -0.0482731  |  0.0322618  |  0.013483   |  0.00733298  |
| 1,4-Butanediol                                |  0.0501615   | -0.183084   |  0.070711   | -0.00968346 |  0.0367001  |  0.0351948   |
| Phenylethyl Alcohol                           | -0.0013864   |  0.114126   | -0.088896   |  0.0865601  | -0.147566   |  0.0371625   |
| Acetophenone, 2'-amino-                       |  0.0317461   |  0.0247866  |  0.0277993  | -0.452704   |  0.0383099  |  0.330063    |
| 2-Tridecanol                                  |  0.0566713   |  0.00395801 | -0.474283   |  0.0230735  |  0.388735   |  0.00184505  |
| Tetradecanal                                  | -0.0521117   |  0.0173687  |  0.149872   |  0.0291456  | -0.161441   |  0.0171662   |
| 1-Dodecanol                                   |  0.0573272   |  0.0427106  |  0.068674   |  0.0536239  | -0.244159   |  0.0218229   |
| Methyl tetradecanoate                         |  0.0713829   | -0.0556794  | -0.336668   |  0.00604146 |  0.321133   | -0.00620971  |
| 2-Pentadecanone                               |  0.124908    | -0.0491257  | -0.182311   |  0.0112922  |  0.0787095  |  0.0165267   |
| Tetradecanoic acid, ethyl ester               | -0.0469712   | -0.0117647  |  0.063278   |  0.0282242  | -0.0377037  |  0.00493738  |
| Hexadecanal                                   | -0.0100448   |  0.0183656  |  0.222512   |  0.00694864 | -0.252176   |  0.0143939   |
| n-Tridecan-1-ol                               |  0.0973948   | -0.031107   | -0.136436   |  0.00130361 |  0.0252045  |  0.0436397   |
| 1-Tetradecanol                                |  0.0571773   |  0.0787576  |  0.445437   |  0.0688769  | -0.702978   |  0.0527293   |
| n-Pentadecanol                                |  0.0015776   | -0.0320737  |  0.256787   | -0.052872   | -0.160116   | -0.0133032   |
| 1-Hexadecanol                                 |  0.0776509   | -0.0423714  |  0.279244   |  0.00403445 | -0.335046   |  0.0164884   |
| Indole                                        | -0.24984     |  0.053358   |  0.334647   | -0.0357336  | -0.0720801  | -0.0303513   |


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
