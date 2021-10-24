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

21.8 seconds

### Metric details
|           |     EC_A |     EC_B |     PA_A |     PA_B |   SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|---------:|-------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.833333 | 0.555556 | 1        |      1 | 1        |   0.833333 |    0.898148 |       0.898148 |  0.456629 |
| recall    | 0.8      | 1        | 1        | 0.4      |      1 | 0.8      |   0.833333 |    0.833333 |       0.833333 |  0.456629 |
| f1-score  | 0.888889 | 0.909091 | 0.714286 | 0.571429 |      1 | 0.888889 |   0.833333 |    0.828764 |       0.828764 |  0.456629 |
| support   | 5        | 5        | 5        | 5        |      5 | 5        |   0.833333 |   30        |      30        |  0.456629 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   4 |                   1 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   3 |                   2 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   1 |                   0 |                   0 |                   4 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |        EC_A |        EC_B |         PA_A |         PA_B |         SA_A |       SA_B |
|:----------------------------------------------|------------:|------------:|-------------:|-------------:|-------------:|-----------:|
| intercept                                     | -0.110777   |  0.021027   | -0.112085    |  0.000731518 | -0.185572    |  0.386675  |
| Ethyl Acetate                                 |  0.219125   |  0.0366677  | -0.158108    | -0.109852    | -0.0776998   |  0.0898668 |
| Ethanol                                       |  0.166125   | -0.0157954  | -0.182345    | -0.0469078   |  0.238898    | -0.159976  |
| Propanoic acid, ethyl ester                   |  0.0886884  | -0.0735989  | -0.000829472 | -0.00246587  | -8.81945e-05 | -0.011706  |
| 2-Pentanone                                   | -0.0201023  |  0.0691402  |  0.0135221   | -0.0267377   | -0.215154    |  0.179332  |
| Decane                                        |  0.0499676  | -0.191267   | -0.0125636   |  0.16456     | -0.369178    |  0.358481  |
| Methyl Isobutyl Ketone                        | -0.0623449  | -0.081633   | -0.00832237  |  0.020635    |  0.196784    | -0.0651186 |
| Amylene hydrate                               | -0.0340711  |  0.0877727  |  0.077548    | -0.0940676   | -0.33448     |  0.297298  |
| Butanoic acid, 2-methyl-, methyl ester        | -0.0277314  | -0.019266   | -0.0731201   |  0.236034    | -0.0309864   | -0.0849302 |
| Isobutyl acetate                              |  0.1302     | -0.0420098  | -0.0351494   |  0.00261845  | -0.00782922  | -0.0478301 |
| Methyl isovalerate                            | -0.0432463  | -0.0563589  | -0.0864639   |  0.416947    | -0.0869083   | -0.143969  |
| 1-Propanol                                    |  0.454277   | -0.152629   | -0.0477732   | -0.0555013   | -0.143992    | -0.0543816 |
| Methyl thiolacetate                           | -0.0902887  | -0.0691483  |  0.0904483   |  0.0764067   | -0.683297    |  0.675879  |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.0820659  | -0.0709155  | -0.0801159   | -0.111421    | -0.245513    |  0.590031  |
| 2-Hexanone                                    |  0.0371289  |  0.118435   | -0.0288182   | -0.0524075   | -0.0135953   | -0.0607433 |
| Ethyl isocyanide                              |  0.167253   | -0.114521   | -0.00534376  | -0.00956347  | -0.000414984 | -0.0374099 |
| 1-Propanol, 2-methyl-                         | -0.0402912  | -0.0626259  |  0.0836108   | -0.198701    |  0.0556729   |  0.162335  |
| 2-Pentanol, 2-methyl-                         | -0.133518   |  0.163598   |  0.13111     | -0.0886869   |  0.0488071   | -0.12131   |
| 2-Pentanol                                    | -0.0637907  | -0.0847218  |  0.0446587   |  0.24473     |  0.19969     | -0.340566  |
| 1-Butanol, 3-methyl-, acetate                 | -0.0292483  | -0.0215042  | -0.0343728   | -0.060964    | -0.218628    |  0.364717  |
| 1 - Undecene                                  |  0.0266995  |  0.0151389  | -0.571841    |  0.394535    |  0.0750686   |  0.0603991 |
| 1-Butanol                                     |  0.126488   |  0.0316553  |  0.0645412   |  0.141496    | -0.20383     | -0.16035   |
| 2-Heptanone                                   |  0.0984964  |  0.284636   | -0.123669    |  0.0195398   | -0.10726     | -0.171743  |
| Dodecane                                      |  0.0341805  | -0.05557    |  0.250325    | -0.18122     | -0.0162      | -0.0315158 |
| 1-Butanol, 3-methyl-                          | -0.0458177  |  0.00653282 |  0.029475    |  0.367933    | -0.539616    |  0.181492  |
| S-Methyl 3-methylbutanethioate                | -0.0341185  | -0.0917964  |  0.353768    |  0.00248469  | -0.127744    | -0.102594  |
| 2-Heptanone, 4,6-dimethyl-                    |  0.0554615  | -0.0171076  | -0.0681927   |  0.127134    | -0.0233239   | -0.0739713 |
| 3-Buten-1-ol, 3-methyl-                       | -0.0819704  | -0.15394    | -0.15825     |  0.0654293   |  0.0614077   |  0.267323  |
| Thiocyanic acid, methyl ester                 | -0.0288345  | -0.0292428  | -0.240138    |  0.448754    | -0.0442533   | -0.106286  |
| Acetoin                                       |  0.0801603  | -0.155629   | -0.133225    | -0.150754    |  0.330954    |  0.0284935 |
| 1-Pentanol, 2-methyl-                         |  0.16625    | -0.0507058  | -0.0277047   | -0.0296904   | -0.00976072  | -0.0483881 |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester | -0.0214132  | -0.0576081  |  0.320134    | -0.0831346   | -0.0646414   | -0.0933362 |
| 2-Heptanol, 4-methyl-                         | -0.0108087  | -0.0321116  |  0.235688    | -0.0972302   | -0.0411949   | -0.0543421 |
| 2-Nonanone                                    | -0.350918   |  0.373377   | -0.0195702   |  0.414043    | -0.23219     | -0.184742  |
| Acetic acid                                   | -0.158847   |  0.0851931  |  0.0121881   | -0.0325138   |  0.0389196   |  0.0550599 |
| 2-Nonanol                                     |  0.0468759  |  0.036832   | -0.492219    |  0.20078     |  0.0990416   |  0.10869   |
| Pyrrole                                       | -0.0189301  | -0.0365851  | -0.0697501   |  0.14317     |  0.00695714  | -0.0248616 |
| 1H-Pyrrole, 2-methyl-                         | -0.0373478  | -0.0794607  |  0.0718814   |  0.259832    | -0.0889288   | -0.125976  |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.113242   |  0.140197   | -0.0553422   | -0.0478886   | -0.0803912   | -0.0698168 |
| Propanoic acid                                |  0.0903845  |  0.03429    | -0.0663533   | -0.0782549   | -0.352385    |  0.372319  |
| Propanoic acid, 2-methyl-                     | -0.00709633 | -0.00345063 | -0.00412947  | -0.00889855  |  0.382158    | -0.358583  |
| 1-Octanol                                     |  0.354653   |  0.130627   | -0.064195    | -0.092244    | -0.247265    | -0.0815756 |
| 2-Undecanone                                  | -0.385083   | -0.0167718  | -0.248085    |  0.118379    |  0.34861     |  0.182951  |
| Benzoic acid, methyl ester                    |  0.150368   |  0.188219   |  0.0511223   | -0.148298    | -0.143744    | -0.097668  |
| Butyrolactone                                 | -0.00932821 | -0.0128356  | -0.0355653   | -0.0426395   | -0.102932    |  0.203301  |
| Decanoic acid, ethyl ester                    |  0.0172027  |  0.0216829  | -0.0069089   | -0.0139105   | -0.00279326  | -0.015273  |
| Acetic acid, decyl ester                      | -0.0876377  |  0.141899   | -0.00696567  | -0.0181585   | -0.00225523  | -0.0268819 |
| 2-Undecanol                                   | -0.033547   | -0.0215355  |  0.0616556   |  0.47053     | -0.278185    | -0.198918  |
| Butanoic acid, 3-methyl-                      | -0.0725215  | -0.0775986  | -0.0703276   | -0.108903    |  0.294649    |  0.0347018 |
| 2-Dodecanone                                  |  0.0811475  |  0.039534   | -0.0384342   | -0.0178341   | -0.0282886   | -0.0361246 |
| 1-Decanol                                     | -0.176692   | -0.086684   |  0.0502298   |  0.0352208   |  0.124398    |  0.0535264 |
| 2-Tridecanone                                 |  0.0589994  |  0.113243   | -0.0439613   | -0.0226231   | -0.0579997   | -0.0476587 |
| Dodecanoic acid, ethyl ester                  |  0.0686437  | -0.0389852  | -0.004016    | -0.00862464  | -0.00145634  | -0.0155615 |
| 1,4-Butanediol                                | -0.00932821 | -0.0128356  | -0.0355653   | -0.0426395   | -0.102932    |  0.203301  |
| Phenylethyl Alcohol                           |  0.241235   |  0.175332   | -0.0504655   | -0.0880222   | -0.200814    | -0.0772655 |
| Acetophenone, 2'-amino-                       |  0.0629811  |  0.107024   | -0.44157     | -0.103732    |  0.20479     |  0.170507  |
| 2-Tridecanol                                  | -0.0909524  |  0.267768   | -0.0247009   | -0.0411204   | -0.0603255   | -0.050669  |
| Tetradecanal                                  |  0.0886884  | -0.0735989  | -0.000829472 | -0.00246587  | -8.81945e-05 | -0.011706  |
| 1-Dodecanol                                   |  0.150268   | -0.431078   |  0.0497503   |  0.0806679   |  0.0919453   |  0.0584462 |
| Methyl tetradecanoate                         | -0.222978   |  0.350676   | -0.0301141   | -0.0300154   | -0.0289533   | -0.0386152 |
| 2-Pentadecanone                               | -0.0871532  |  0.287627   | -0.0440667   | -0.0362719   | -0.0689242   | -0.0512107 |
| Tetradecanoic acid, ethyl ester               |  0.0886884  | -0.0735989  | -0.000829472 | -0.00246587  | -8.81945e-05 | -0.011706  |
| Hexadecanal                                   |  0.0939928  |  0.138315   | -0.0379089   | -0.0318658   | -0.114193    | -0.0483393 |
| n-Tridecan-1-ol                               | -0.065853   |  0.258744   | -0.0521789   | -0.0304625   | -0.0628647   | -0.0473851 |
| 1-Tetradecanol                                |  0.143417   | -0.378513   |  0.0393584   |  0.0816976   |  0.0540652   |  0.059975  |
| n-Pentadecanol                                |  0.329583   | -0.221495   | -0.0265114   | -0.0118086   | -0.0326965   | -0.0370724 |
| 1-Hexadecanol                                 |  0.521972   | -0.126532   | -0.0536695   | -0.0494268   | -0.224081    | -0.0682626 |
| Indole                                        |  0.0550825  | -0.13566    |  0.0269287   |  0.0336868   | -0.00771792  |  0.0276799 |


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
