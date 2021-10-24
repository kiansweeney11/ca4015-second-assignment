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

26.5 seconds

### Metric details
|           |     EC_A |     EC_B |     PA_A |   PA_B |     SA_A |   SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|-------:|---------:|-------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.217391 | 1        |      0 | 0.5      |      0 |   0.366667 |    0.452899 |       0.452899 |   1.35751 |
| recall    | 0.2      | 1        | 0.8      |      0 | 0.2      |      0 |   0.366667 |    0.366667 |       0.366667 |   1.35751 |
| f1-score  | 0.333333 | 0.357143 | 0.888889 |      0 | 0.285714 |      0 |   0.366667 |    0.310847 |       0.310847 |   1.35751 |
| support   | 5        | 5        | 5        |      5 | 5        |      5 |   0.366667 |   30        |      30        |   1.35751 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   1 |                   4 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   1 |                   4 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   4 |                   0 |                   0 |                   1 |                   0 |
| Labeled as SA_B |                   0 |                   4 |                   0 |                   0 |                   1 |                   0 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |         EC_A |        EC_B |        PA_A |         PA_B |         SA_A |        SA_B |
|:----------------------------------------------|-------------:|------------:|------------:|-------------:|-------------:|------------:|
| intercept                                     | -0.00110007  | -0.116786   |  0.138558   | -0.223269    | -0.330264    |  0.532861   |
| Ethyl Acetate                                 |  0.179938    | -0.0102728  | -0.291707   |  0.2278      |  0.127912    | -0.23367    |
| Ethanol                                       |  0.244845    | -0.106327   | -0.218509   |  0.0552365   |  0.116585    | -0.0918305  |
| Propanoic acid, ethyl ester                   |  0.0967155   | -0.0785811  | -0.00479647 | -0.00537548  | -0.000621804 | -0.0073406  |
| 2-Pentanone                                   | -0.00186699  | -0.0258678  | -0.115412   |  0.138006    |  0.369999    | -0.364858   |
| Decane                                        |  0.0391035   | -0.166792   |  0.128413   |  0.182206    | -0.521957    |  0.339027   |
| Methyl Isobutyl Ketone                        | -0.04339     | -0.0411806  | -0.0142891  | -0.0519214   | -0.443948    |  0.594729   |
| Amylene hydrate                               | -0.00566737  |  0.0352091  |  0.0183263  | -0.0556423   | -0.430139    |  0.437914   |
| Butanoic acid, 2-methyl-, methyl ester        | -0.0551562   | -0.0362838  |  0.0560919  |  0.282776    | -0.0827676   | -0.16466    |
| Isobutyl acetate                              |  0.143011    | -0.0821146  | -0.11619    |  0.15577     | -0.0458712   | -0.0546057  |
| Methyl isovalerate                            | -0.0748156   | -0.0510464  |  0.121843   |  0.308642    | -0.111472    | -0.193151   |
| 1-Propanol                                    |  0.446567    | -0.233184   | -0.0638204  | -0.0185566   | -0.0617763   | -0.0692291  |
| Methyl thiolacetate                           | -0.120807    | -0.101634   |  0.11349    |  0.128326    | -0.177884    |  0.158509   |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.102612    | -0.0914185  | -0.137801   | -0.112211    |  0.336505    |  0.107537   |
| 2-Hexanone                                    | -0.000163784 |  0.136844   | -0.0521596  | -0.0278554   | -0.0174455   | -0.0392199  |
| Ethyl isocyanide                              |  0.0681217   | -0.00871001 | -0.0138666  | -0.0132752   | -0.00137099  | -0.0308989  |
| 1-Propanol, 2-methyl-                         | -0.051218    | -0.0521755  |  0.153551   | -0.123897    |  0.0406711   |  0.0330689  |
| 2-Pentanol, 2-methyl-                         | -0.0996863   |  0.075095   |  0.308074   | -0.222418    |  0.0235497   | -0.0846137  |
| 2-Pentanol                                    | -0.0637607   | -0.0613441  |  0.308081   |  0.133885    | -0.0112787   | -0.305583   |
| 1-Butanol, 3-methyl-, acetate                 | -0.0247569   | -0.0157398  | -0.0280786  | -0.0444177   | -0.332721    |  0.445714   |
| 1 - Undecene                                  | -0.000668829 | -0.0098111  | -0.409933   |  0.442492    | -0.0143485   | -0.00772991 |
| 1-Butanol                                     |  0.0592682   |  0.0655778  |  0.448563   | -0.210532    | -0.137278    | -0.2256     |
| 2-Heptanone                                   |  0.0717568   |  0.239752   | -0.065442   |  0.0671412   | -0.112147    | -0.201062   |
| Dodecane                                      |  0.0192427   | -0.0448308  |  0.293799   | -0.216913    | -0.0286083   | -0.0226897  |
| 1-Butanol, 3-methyl-                          | -0.0217606   | -0.0301634  |  0.0068833  |  0.242545    | -0.675251    |  0.477747   |
| S-Methyl 3-methylbutanethioate                | -0.0668836   | -0.0430452  |  0.342968   | -0.000570931 | -0.077145    | -0.155323   |
| 2-Heptanone, 4,6-dimethyl-                    |  0.0526105   | -0.0358889  |  0.234458   | -0.0598086   | -0.0554577   | -0.135913   |
| 3-Buten-1-ol, 3-methyl-                       | -0.0396304   | -0.13552    | -0.228459   |  0.23906     |  0.0258463   |  0.138702   |
| Thiocyanic acid, methyl ester                 | -0.0207565   | -0.021866   | -0.217774   |  0.410232    | -0.0664528   | -0.0833825  |
| Acetoin                                       |  0.0203748   | -0.20969    | -0.183341   | -0.0967581   |  0.53304     | -0.0636254  |
| 1-Pentanol, 2-methyl-                         |  0.181008    | -0.071907   | -0.0524239  | -0.0178157   | -0.0111917   | -0.02767    |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester | -0.0342563   | -0.0348901  |  0.0475281  |  0.209643    | -0.0411114   | -0.146913   |
| 2-Heptanol, 4-methyl-                         | -0.0122294   | -0.0120601  |  0.203875   | -0.0851614   | -0.00530028  | -0.0891238  |
| 2-Nonanone                                    | -0.508802    |  0.169584   | -0.364183   |  0.135279    |  0.213681    |  0.354441   |
| Acetic acid                                   | -0.20352     |  0.146797   |  0.0294495  | -0.0384594   |  0.042815    |  0.0229185  |
| 2-Nonanol                                     | -0.0433368   | -0.0621789  |  0.0161661  |  0.33752     | -0.0859446   | -0.162226   |
| Pyrrole                                       | -0.0730151   | -0.0714534  |  0.403112   |  0.0622742   | -0.0925056   | -0.228412   |
| 1H-Pyrrole, 2-methyl-                         | -0.0536986   | -0.05242    |  0.152442   |  0.21108     | -0.0788465   | -0.178558   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.125345    |  0.0917272  | -0.0959236  | -0.00531287  | -0.0554973   | -0.0603389  |
| Propanoic acid                                |  0.0840697   |  0.0995785  | -0.105348   | -0.0514896   | -0.713057    |  0.686246   |
| Propanoic acid, 2-methyl-                     | -0.0138566   | -0.00729254 | -0.00745562 | -0.0291435   |  0.429198    | -0.37145    |
| 1-Octanol                                     |  0.295429    |  0.0510509  | -0.0659158  | -0.0547204   | -0.155205    | -0.0706387  |
| 2-Undecanone                                  | -0.0776184   |  0.194162   | -0.041695   |  0.389597    | -0.167161    | -0.297284   |
| Benzoic acid, methyl ester                    |  0.219931    |  0.0776151  |  0.0294105  | -0.129367    | -0.116426    | -0.0811638  |
| Butyrolactone                                 | -0.0446729   | -0.0544968  | -0.103377   | -0.0456083   |  0.490251    | -0.242096   |
| Decanoic acid, ethyl ester                    |  0.0183899   |  0.0367417  | -0.0109766  | -0.0133815   | -0.0156156   | -0.0151579  |
| Acetic acid, decyl ester                      | -0.0534439   |  0.101975   | -0.00704099 | -0.0145189   | -0.00373018  | -0.0232407  |
| 2-Undecanol                                   | -0.0928486   |  0.0889372  |  0.260207   |  0.0147256   | -0.110666    | -0.160355   |
| Butanoic acid, 3-methyl-                      | -0.00966406  | -0.0154153  | -0.013983   | -0.0419595   |  0.46255     | -0.381529   |
| 2-Dodecanone                                  |  0.113063    |  0.0366876  | -0.0672266  | -0.00850308  | -0.00928985  | -0.064731   |
| 1-Decanol                                     |  0.0665597   |  0.258185   | -0.0750598  | -0.0440302   | -0.13158     | -0.0740747  |
| 2-Tridecanone                                 | -0.239295    | -0.283112   |  0.09852    |  0.0626865   |  0.206469    |  0.154731   |
| Dodecanoic acid, ethyl ester                  | -0.0203451   |  0.0489995  | -0.00449402 | -0.0109094   | -0.00234788  | -0.0109031  |
| 1,4-Butanediol                                | -0.0365965   | -0.0444631  | -0.0895853  | -0.0418875   |  0.123391    |  0.0891418  |
| Phenylethyl Alcohol                           |  0.144944    |  0.126584   | -0.050237   | -0.0503552   | -0.114644    | -0.056292   |
| Acetophenone, 2'-amino-                       | -0.0509048   | -0.0571817  | -0.262234   |  0.641627    | -0.0940256   | -0.177281   |
| 2-Tridecanol                                  | -0.135697    |  0.284547   | -0.0252282  | -0.0212193   | -0.0143472   | -0.0880548  |
| Tetradecanal                                  |  0.0723835   | -0.0552219  | -0.00443322 | -0.0066421   | -0.00156005  | -0.0045262  |
| 1-Dodecanol                                   | -0.0123368   | -0.442061   |  0.106218   |  0.0432136   |  0.119491    |  0.185475   |
| Methyl tetradecanoate                         | -0.256056    |  0.407625   | -0.0468395  | -0.0178628   | -0.01135     | -0.0755173  |
| 2-Pentadecanone                               | -0.0394628   |  0.258382   | -0.0619183  | -0.0187833   | -0.0175654   | -0.120652   |
| Tetradecanoic acid, ethyl ester               |  0.0427897   | -0.0235971  | -0.00320752 | -0.00748619  | -0.000966531 | -0.0075323  |
| Hexadecanal                                   |  0.222523    | -0.0166181  | -0.0424139  | -0.0252174   | -0.0304818   | -0.107792   |
| n-Tridecan-1-ol                               | -0.0317971   |  0.257995   | -0.0939831  | -0.0113083   | -0.0146483   | -0.106258   |
| 1-Tetradecanol                                |  0.237867    | -0.565975   |  0.0788136  |  0.030081    |  0.086468    |  0.132745   |
| n-Pentadecanol                                |  0.33632     | -0.178738   | -0.0523537  | -0.00807913  | -0.00869739  | -0.0884513  |
| 1-Hexadecanol                                 |  0.517516    | -0.162237   | -0.0708516  | -0.039995    | -0.117331    | -0.127101   |
| Indole                                        |  0.0877291   | -0.181996   |  0.0413678  |  0.00105284  | -0.012503    |  0.0643496  |


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
