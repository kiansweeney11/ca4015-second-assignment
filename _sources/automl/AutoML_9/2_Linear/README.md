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

21.2 seconds

### Metric details
|           |   EC_A |   EC_B |   PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------:|-------:|-------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |      1 |      1 |      1 |      1 | 0.833333 | 1        |   0.966667 |    0.972222 |       0.972222 |  0.377057 |
| recall    |      1 |      1 |      1 |      1 | 1        | 0.8      |   0.966667 |    0.966667 |       0.966667 |  0.377057 |
| f1-score  |      1 |      1 |      1 |      1 | 0.909091 | 0.888889 |   0.966667 |    0.96633  |       0.96633  |  0.377057 |
| support   |      5 |      5 |      5 |      5 | 5        | 5        |   0.966667 |   30        |      30        |  0.377057 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   5 |                   0 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   0 |                   5 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   1 |                   4 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |        EC_A |         EC_B |         PA_A |        PA_B |         SA_A |        SA_B |
|:----------------------------------------------|------------:|-------------:|-------------:|------------:|-------------:|------------:|
| intercept                                     |  0.00280639 | -0.03259     |  0.0785835   | -0.168428   | -0.31203     |  0.431658   |
| Ethyl Acetate                                 |  0.198526   |  0.0178657   | -0.27283     |  0.132604   | -0.0840475   |  0.00788208 |
| Ethanol                                       |  0.240097   | -0.0824367   | -0.406584    |  0.0991996  |  0.0495597   |  0.100165   |
| Propanoic acid, ethyl ester                   |  0.0710106  | -0.0574384   | -0.000265893 | -0.00494042 | -0.000106374 | -0.00825961 |
| 2-Pentanone                                   | -0.0214244  | -0.0202793   | -0.0586098   |  0.165398   | -0.0814461   |  0.0163619  |
| Decane                                        |  0.00795617 | -0.198158    |  0.0131509   |  0.229176   | -0.488285    |  0.43616    |
| Methyl Isobutyl Ketone                        | -0.0477052  | -0.0406596   |  0.0525372   | -0.131984   |  0.111394    |  0.0564182  |
| Amylene hydrate                               | -0.0518663  |  0.0356348   |  0.0147443   | -0.068228   | -0.2095      |  0.279215   |
| Butanoic acid, 2-methyl-, methyl ester        | -0.0201531  | -0.0158763   | -0.00857495  |  0.102545   | -0.00969276  | -0.0482479  |
| Isobutyl acetate                              |  0.13801    | -0.0470421   | -0.026182    | -0.0138996  | -0.0105159   | -0.0403702  |
| Methyl isovalerate                            | -0.03122    | -0.0489446   | -0.11585     |  0.376533   | -0.0550555   | -0.125463   |
| 1-Propanol                                    |  0.487156   | -0.244183    | -0.0697724   | -0.027641   | -0.0941883   | -0.0513719  |
| Methyl thiolacetate                           | -0.144569   | -0.0672294   |  0.0729018   |  0.1068     | -0.640678    |  0.672775   |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.0275593  | -0.0439943   | -0.0481015   | -0.0285311  | -0.0555982   |  0.203784   |
| 2-Hexanone                                    |  0.0236626  |  0.132627    | -0.021483    | -0.0642882  | -0.016452    | -0.0540666  |
| Ethyl isocyanide                              |  0.0728878  |  0.00105443  | -0.00267622  | -0.022901   | -0.00175405  | -0.046611   |
| 1-Propanol, 2-methyl-                         | -0.105024   | -0.0651179   |  0.0872479   | -0.124671   |  0.00957599  |  0.197989   |
| 2-Pentanol, 2-methyl-                         | -0.0807597  |  0.0395187   |  0.07813     | -0.180898   |  0.464365    | -0.320356   |
| 2-Pentanol                                    | -0.0636866  | -0.0631312   |  0.174752    |  0.201591   |  0.0933988   | -0.342924   |
| 1-Butanol, 3-methyl-, acetate                 | -0.0536403  | -0.0361881   | -0.069502    | -0.086416   | -0.123251    |  0.368997   |
| 1 - Undecene                                  |  0.0908646  |  0.0890878   | -0.766036    |  0.128633   |  0.221631    |  0.235821   |
| 1-Butanol                                     |  0.0632643  |  0.125339    | -0.00541743  |  0.202195   | -0.163978    | -0.221403   |
| 2-Heptanone                                   |  0.10969    |  0.274478    | -0.172856    |  0.107126   | -0.159701    | -0.158737   |
| Dodecane                                      |  0.0660057  | -0.0917799   |  0.32423     | -0.207765   | -0.0391001   | -0.0515909  |
| 1-Butanol, 3-methyl-                          | -0.0764285  | -0.0142416   | -0.00125099  |  0.257076   | -0.490211    |  0.325056   |
| S-Methyl 3-methylbutanethioate                |  0.00651861 | -0.000681321 |  0.0236036   | -0.0573619  |  0.0698798   | -0.0419589  |
| 2-Heptanone, 4,6-dimethyl-                    |  0.059206   | -0.0128729   |  0.0053134   |  0.0236327  | -0.0173017   | -0.0579775  |
| 3-Buten-1-ol, 3-methyl-                       | -0.0908084  | -0.10125     | -0.32041     |  0.305191   | -0.0637255   |  0.271003   |
| Thiocyanic acid, methyl ester                 | -0.0112484  | -0.00642637  | -0.265048    |  0.327451   | -0.00704597  | -0.0376818  |
| Acetoin                                       | -0.0274968  | -0.186857    | -0.238491    | -0.129231   |  0.597213    | -0.0151368  |
| 1-Pentanol, 2-methyl-                         |  0.137676   | -0.0223486   | -0.0236926   | -0.0377188  | -0.0171622   | -0.0367537  |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester | -0.0335088  | -0.0430101   |  0.163352    |  0.14047    | -0.0376156   | -0.189688   |
| 2-Heptanol, 4-methyl-                         | -0.0108569  | -0.00996723  |  0.25092     | -0.185011   | -0.0184242   | -0.0266611  |
| 2-Nonanone                                    | -0.502585   |  0.19342     | -0.393879    |  0.17053    |  0.3401      |  0.192414   |
| Acetic acid                                   | -0.335751   |  0.0579488   |  0.120583    |  0.0266079  |  0.121726    |  0.00888451 |
| 2-Nonanol                                     | -0.0223268  | -0.0726204   | -0.0492909   |  0.291346   | -0.0769025   | -0.0702052  |
| Pyrrole                                       | -0.0515878  | -0.0628459   |  0.0522478   |  0.218842   | -0.084666    | -0.0719899  |
| 1H-Pyrrole, 2-methyl-                         | -0.0586079  | -0.0602553   |  0.182667    |  0.215056   | -0.112669    | -0.16619    |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.164874   |  0.0933458   | -0.0301448   | -0.0702316  | -0.0925198   | -0.0653232  |
| Propanoic acid                                |  0.014061   |  0.0461327   | -0.167421    | -0.101099   | -0.458783    |  0.667109   |
| Propanoic acid, 2-methyl-                     | -0.0319388  | -0.0172253   | -0.0294998   | -0.0533255  |  0.616739    | -0.48475    |
| 1-Octanol                                     |  0.344928   |  0.155506    | -0.0942013   | -0.0873183  | -0.23145     | -0.0874646  |
| 2-Undecanone                                  | -0.13649    |  0.243226    | -0.0105196   |  0.486593   | -0.245565    | -0.337245   |
| Benzoic acid, methyl ester                    |  0.204132   |  0.166235    |  0.0429068   | -0.185521   | -0.145737    | -0.0820157  |
| Butyrolactone                                 | -0.0132957  | -0.0164192   | -0.0666456   | -0.0133742  | -0.061894    |  0.171629   |
| Decanoic acid, ethyl ester                    |  0.0229812  |  0.0427408   | -0.0136521   | -0.014596   | -0.0160117   | -0.0214621  |
| Acetic acid, decyl ester                      | -0.0849337  |  0.152569    | -0.00439487  | -0.023295   | -0.00378117  | -0.0361647  |
| 2-Undecanol                                   | -0.0985693  |  0.0822719   |  0.192357    |  0.151465   | -0.202164    | -0.125361   |
| Butanoic acid, 3-methyl-                      |  0.0963977  |  0.0529833   |  0.12179     |  0.0725208  | -0.0615497   | -0.282142   |
| 2-Dodecanone                                  |  0.0864271  |  0.0287493   | -0.0573523   | -0.00715388 | -0.0218148   | -0.0288554  |
| 1-Decanol                                     | -0.118868   |  0.104804    |  0.036481    | -0.0330122  | -0.00727098  |  0.0178667  |
| 2-Tridecanone                                 | -0.0159476  | -0.0790932   | -0.000391746 |  0.0257989  |  0.0808142   | -0.0111806  |
| Dodecanoic acid, ethyl ester                  | -0.0156972  |  0.0488443   | -0.00290902  | -0.0109194  | -0.00211299  | -0.0172057  |
| 1,4-Butanediol                                | -0.0132957  | -0.0164192   | -0.0666456   | -0.0133742  | -0.061894    |  0.171629   |
| Phenylethyl Alcohol                           |  0.213712   |  0.193121    | -0.063951    | -0.0866074  | -0.177694    | -0.0785797  |
| Acetophenone, 2'-amino-                       | -0.0373856  | -0.0848202   | -0.038958    |  0.436323   | -0.0912129   | -0.183947   |
| 2-Tridecanol                                  | -0.0881005  |  0.258671    | -0.0257566   | -0.0453743  | -0.0386265   | -0.0608135  |
| Tetradecanal                                  |  0.0710106  | -0.0574384   | -0.000265893 | -0.00494042 | -0.000106374 | -0.00825961 |
| 1-Dodecanol                                   |  0.0931739  | -0.465197    |  0.0981662   |  0.0605671  |  0.134509    |  0.0787811  |
| Methyl tetradecanoate                         | -0.255374   |  0.385537    | -0.0292212   | -0.0267859  | -0.0218561   | -0.0522995  |
| 2-Pentadecanone                               | -0.10183    |  0.294271    | -0.0604298   | -0.0228915  | -0.045189    | -0.0639307  |
| Tetradecanoic acid, ethyl ester               |  0.0303154  | -0.007464    | -0.000342163 | -0.00808022 | -0.000135235 | -0.0142938  |
| Hexadecanal                                   |  0.139752   |  0.0805393   | -0.0711024   | -0.0205665  | -0.0664803   | -0.0621425  |
| n-Tridecan-1-ol                               | -0.0958348  |  0.263252    | -0.0671733   | -0.0102717  | -0.0442438   | -0.0457287  |
| 1-Tetradecanol                                |  0.236489   | -0.546924    |  0.0685436   |  0.0655162  |  0.110376    |  0.0659993  |
| n-Pentadecanol                                |  0.30911    | -0.19558     | -0.0520207   | -0.00701429 | -0.0208857   | -0.0336096  |
| 1-Hexadecanol                                 |  0.50343    | -0.0962736   | -0.105243    | -0.043251   | -0.173153    | -0.0855099  |
| Indole                                        | -0.0718461  | -0.23276     |  0.0829723   |  0.0424704  |  0.10262     |  0.0765434  |


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
