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

19.5 seconds

### Metric details
|           |   0 |   1 |   2 |   3 |   4 |   5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|----:|----:|----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0612634 |
| recall    |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0612634 |
| f1-score  |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0612634 |
| support   |   5 |   5 |   5 |   5 |   5 |   5 |          1 |          30 |             30 | 0.0612634 |


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
|                                               |            0 |           1 |           2 |           3 |            4 |            5 |
|:----------------------------------------------|-------------:|------------:|------------:|------------:|-------------:|-------------:|
| intercept                                     |  0.159355    |  0.70994    | -0.155577   | -0.174244   | -0.194724    | -0.344749    |
| Ethyl Acetate                                 | -0.0747072   |  0.0377979  |  0.267289   | -0.15433    |  0.0718333   | -0.147882    |
| Ethanol                                       | -0.0607176   | -0.00206732 |  0.364208   | -0.218855   | -0.0178701   | -0.0646977   |
| Propanoic acid, ethyl ester                   |  0.0677665   |  0.0381247  |  0.0201613  |  0.0595406  | -0.227207    |  0.0416141   |
| 2-Pentanone                                   |  0.0133258   | -0.0372495  |  0.124913   | -0.044248   |  0.0252829   | -0.082024    |
| Decane                                        | -0.370737    |  0.338285   | -0.0176053  |  0.0677237  | -0.166486    |  0.148819    |
| Methyl Isobutyl Ketone                        |  0.0503923   |  0.244333   | -0.0690487  | -0.101292   | -0.00790314  | -0.116482    |
| Amylene hydrate                               | -0.415213    |  0.393437   |  0.0958344  |  0.0148695  |  0.0105071   | -0.0994356   |
| Butanoic acid, 2-methyl-, methyl ester        |  0.0828719   |  0.00421177 | -0.00424161 | -0.338274   |  0.0432103   |  0.212221    |
| Isobutyl acetate                              |  0.149766    |  0.0976827  |  0.165869   | -0.232933   | -0.147082    | -0.0333015   |
| Methyl isovalerate                            | -0.206997    | -0.401745   |  0.071141   |  0.0125309  |  0.0170435   |  0.508027    |
| 1-Propanol                                    | -0.0158594   | -0.0801664  |  0.297172   |  0.00760231 | -0.218778    |  0.0100296   |
| Methyl thiolacetate                           | -0.74972     |  0.765713   | -0.136025   |  0.116907   | -0.0992672   |  0.102392    |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.440547    |  0.372548   |  0.0275183  |  0.0379568  | -0.0300274   |  0.0325514   |
| 2-Hexanone                                    | -0.236307    | -0.447965   |  0.0540617  |  0.190685   |  0.311233    |  0.128293    |
| Ethyl isocyanide                              |  0.0424974   | -0.0151219  | -0.082244   |  0.0413739  |  0.00141635  |  0.0120782   |
| 1-Propanol, 2-methyl-                         | -0.169423    |  0.240109   |  0.0546651  |  0.0789283  | -0.110116    | -0.0941636   |
| 2-Pentanol, 2-methyl-                         | -0.0220093   | -0.273329   | -0.0187065  |  0.251997   |  0.10539     | -0.0433421   |
| 2-Pentanol                                    | -0.046808    | -0.419109   |  0.0672897  |  0.171212   |  0.0295793   |  0.197836    |
| 1-Butanol, 3-methyl-, acetate                 | -0.146694    |  0.264994   | -0.0298369  | -0.0398638  |  0.0013412   | -0.0499402   |
| 1 - Undecene                                  | -0.0123266   |  0.0725258  |  0.0341408  | -0.537083   |  0.0113578   |  0.431385    |
| 1-Butanol                                     |  0.0136561   |  0.0699512  |  0.174426   | -0.199956   | -0.00435878  | -0.0537193   |
| 2-Heptanone                                   | -0.049905    | -0.238464   |  0.236383   | -0.0751546  |  0.158287    | -0.0311462   |
| Dodecane                                      |  0.0740413   | -0.0265003  | -0.140909   |  0.309035   | -0.0968395   | -0.118828    |
| 1-Butanol, 3-methyl-                          | -0.242513    | -0.117351   | -0.0713577  |  0.27065    | -0.055369    |  0.21594     |
| S-Methyl 3-methylbutanethioate                |  0.0169118   |  0.0410742  |  0.0248227  |  0.0384284  |  0.026833    | -0.14807     |
| 2-Heptanone, 4,6-dimethyl-                    |  0.210736    |  0.120574   | -0.0402288  | -0.177323   | -0.0852624   | -0.0284957   |
| 3-Buten-1-ol, 3-methyl-                       |  0.269212    | -0.0628218  | -0.123541   | -0.184607   |  0.0311222   |  0.0706355   |
| Thiocyanic acid, methyl ester                 |  0.112679    |  0.0399245  |  0.011013   | -0.443667   |  0.0640597   |  0.215991    |
| Acetoin                                       |  0.532369    | -0.0661328  |  0.132852   | -0.215952   | -0.239019    | -0.144118    |
| 1-Pentanol, 2-methyl-                         |  0.130801    |  0.0382155  | -0.090068   |  0.110415   | -0.259298    |  0.0699351   |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester |  0.0797351   |  0.0171887  |  0.0119869  |  0.138506   |  0.0417446   | -0.289161    |
| 2-Heptanol, 4-methyl-                         |  0.023721    | -0.0540177  | -0.0071555  |  0.150102   |  0.000619888 | -0.11327     |
| 2-Nonanone                                    | -0.0395262   |  0.116107   | -0.38995    | -0.174291   |  0.202979    |  0.284681    |
| Acetic acid                                   |  0.036934    |  0.0922136  | -0.28422    | -0.00938265 |  0.154756    |  0.00969918  |
| 2-Nonanol                                     | -0.0491231   |  0.0677194  |  0.0404873  | -0.378481   | -0.0188053   |  0.338202    |
| Pyrrole                                       |  0.0110081   |  0.0553154  | -0.00318983 | -0.0797475  | -0.013258    |  0.0298717   |
| 1H-Pyrrole, 2-methyl-                         |  0.00574378  |  0.0262621  |  0.014384   |  0.00550085 | -0.00469858  | -0.0471921   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.119948    |  0.120624   |  0.0576926  | -0.24072    |  0.121479    | -0.179024    |
| Propanoic acid                                | -0.574445    |  0.455151   | -0.147416   | -0.032954   |  0.309441    | -0.00977707  |
| Propanoic acid, 2-methyl-                     |  0.333767    | -0.768707   |  0.100784   |  0.161205   |  0.0805268   |  0.0924244   |
| 1-Octanol                                     | -0.0149067   |  0.0236464  | -0.0114644  |  0.063153   | -0.0816446   |  0.0212163   |
| 2-Undecanone                                  |  0.0235899   |  0.0837256  | -0.222355   | -0.189275   | -0.037651    |  0.341966    |
| Benzoic acid, methyl ester                    |  0.0378575   |  0.119278   |  0.303319   | -0.235307   |  0.0219452   | -0.247093    |
| Butyrolactone                                 | -0.470788    |  0.0045006  |  0.15168    |  0.0968324  |  0.100048    |  0.117727    |
| Decanoic acid, ethyl ester                    |  0.000929104 | -0.046952   |  0.0284291  |  0.00747365 |  0.0125173   | -0.00239724  |
| Acetic acid, decyl ester                      |  0.0355307   | -0.0264288  | -0.117529   |  0.0266747  |  0.077665    |  0.00408693  |
| 2-Undecanol                                   | -0.0346633   | -0.0709423  | -0.145233   | -0.0439641  | -0.0933888   |  0.388191    |
| Butanoic acid, 3-methyl-                      |  0.291021    | -0.218591   | -0.0134626  | -0.0113921  | -0.05208     |  0.004505    |
| 2-Dodecanone                                  |  0.0550806   | -0.0315771  |  0.159677   |  0.0142093  | -0.214554    |  0.0171642   |
| 1-Decanol                                     |  0.0173901   | -0.0135254  | -0.166753   |  0.0296623  |  0.131911    |  0.00131528  |
| 2-Tridecanone                                 |  0.0852823   | -0.0402371  |  0.0270618  |  0.0199009  | -0.11263     |  0.0206221   |
| Dodecanoic acid, ethyl ester                  |  0.0296537   | -0.0248986  | -0.066683   |  0.0223393  |  0.0324989   |  0.00708974  |
| 1,4-Butanediol                                | -0.471059    |  0.00328023 |  0.152057   |  0.0973996  |  0.100232    |  0.118091    |
| Phenylethyl Alcohol                           |  0.0164464   |  0.0666047  | -0.00485331 |  0.111861   | -0.245217    |  0.0551586   |
| Acetophenone, 2'-amino-                       |  0.0315382   | -0.0448627  |  0.0130247  | -0.237662   |  0.0150294   |  0.222932    |
| 2-Tridecanol                                  |  0.0831072   |  0.00182343 | -0.391971   |  0.0250346  |  0.277268    |  0.00473771  |
| Tetradecanal                                  |  0.28786     |  0.274646   | -0.502581   |  0.20552    | -0.400458    |  0.135013    |
| 1-Dodecanol                                   |  0.022512    | -0.0120186  | -0.0285501  |  0.0277318  | -0.0231659   |  0.0134909   |
| Methyl tetradecanoate                         |  0.0709366   | -0.021243   | -0.254792   |  0.00947779 |  0.194445    |  0.00117541  |
| 2-Pentadecanone                               |  0.077882    | -0.0642396  | -0.0787192  | -0.0113911  |  0.077744    | -0.00127607  |
| Tetradecanoic acid, ethyl ester               |  0.0869151   |  0.0445608  | -0.208639   |  0.0718859  | -0.028046    |  0.0333231   |
| Hexadecanal                                   |  0.0609845   | -0.0118262  |  0.0120499  |  0.0286204  | -0.11002     |  0.0201909   |
| n-Tridecan-1-ol                               |  0.0619137   | -0.0527561  |  0.0893321  |  0.00251136 | -0.111266    |  0.0102648   |
| 1-Tetradecanol                                |  0.0655316   |  0.0884517  |  0.320708   |  0.0858482  | -0.626598    |  0.0660586   |
| n-Pentadecanol                                |  0.0192562   | -0.00822622 |  0.159604   | -0.0146798  | -0.15601     |  5.50516e-05 |
| 1-Hexadecanol                                 |  0.109514    |  0.0589779  |  0.0456207  |  0.0477653  | -0.305671    |  0.0437939   |
| Indole                                        | -0.0252095   |  0.0312995  |  0.222125   |  0.0140383  | -0.257841    |  0.0155879   |


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
