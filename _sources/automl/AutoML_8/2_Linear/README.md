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

25.6 seconds

### Metric details
|           |     EC_A |     EC_B |     PA_A |   PA_B |     SA_A |     SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|-------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.833333 | 0.5      |      0 | 0.833333 | 1        |   0.766667 |    0.694444 |       0.694444 |  0.666864 |
| recall    | 0.8      | 1        | 1        |      0 | 1        | 0.8      |   0.766667 |    0.766667 |       0.766667 |  0.666864 |
| f1-score  | 0.888889 | 0.909091 | 0.666667 |      0 | 0.909091 | 0.888889 |   0.766667 |    0.710438 |       0.710438 |  0.666864 |
| support   | 5        | 5        | 5        |      5 | 5        | 5        |   0.766667 |   30        |      30        |  0.666864 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   4 |                   1 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   1 |                   4 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |        EC_A |        EC_B |         PA_A |        PA_B |         SA_A |        SA_B |
|:----------------------------------------------|------------:|------------:|-------------:|------------:|-------------:|------------:|
| intercept                                     | -0.119586   | -0.0921045  |  0.273944    | -0.305515   | -0.181065    |  0.424327   |
| Ethyl Acetate                                 |  0.130658   | -0.0330937  | -0.313466    |  0.182011   |  0.101648    | -0.067758   |
| Ethanol                                       |  0.275634   | -0.0597891  | -0.185454    |  0.0629909  |  0.0872514   | -0.180634   |
| Propanoic acid, ethyl ester                   |  0.0513046  | -0.0470627  | -0.000947475 | -0.00173706 | -0.000162684 | -0.00139463 |
| 2-Pentanone                                   |  0.00903544 | -0.00468456 | -0.176697    |  0.174781   |  0.410904    | -0.413339   |
| Decane                                        | -0.0118968  | -0.180966   |  0.100302    |  0.0927485  | -0.461494    |  0.461307   |
| Methyl Isobutyl Ketone                        | -0.0678115  | -0.0498698  | -0.149219    |  0.0471711  | -0.028602    |  0.248332   |
| Amylene hydrate                               | -0.0164804  |  0.0507858  |  0.0549602   | -0.0452603  | -0.445068    |  0.401063   |
| Butanoic acid, 2-methyl-, methyl ester        | -0.021293   | -0.0188581  |  0.152315    | -0.0251762  | -0.00816861  | -0.0788194  |
| Isobutyl acetate                              |  0.146568   | -0.069775   | -0.178709    |  0.159492   | -0.0112727   | -0.0463037  |
| Methyl isovalerate                            | -0.0462327  | -0.0546501  |  0.0801796   |  0.242651   | -0.0776634   | -0.144284   |
| 1-Propanol                                    |  0.419395   | -0.193227   | -0.078347    | -0.0178434  | -0.0735713   | -0.0564061  |
| Methyl thiolacetate                           | -0.114438   | -0.0859609  |  0.112531    |  0.117056   | -0.903673    |  0.874485   |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.0821512  | -0.0723223  | -0.165373    | -0.0514618  |  0.290079    |  0.0812286  |
| 2-Hexanone                                    |  0.0110522  |  0.158804   | -0.0538737   | -0.0391792  | -0.0510573   | -0.0257461  |
| Ethyl isocyanide                              |  0.023423   |  0.030376   | -0.00822328  | -0.0108223  | -0.000738792 | -0.0340146  |
| 1-Propanol, 2-methyl-                         | -0.0884812  | -0.100516   |  0.0482461   | -0.12883    | -0.15632     |  0.425901   |
| 2-Pentanol, 2-methyl-                         | -0.105428   |  0.0596386  |  0.47862     | -0.320296   |  0.254931    | -0.367466   |
| 2-Pentanol                                    | -0.073336   | -0.0729432  |  0.295205    |  0.0656818  |  0.286507    | -0.501114   |
| 1-Butanol, 3-methyl-, acetate                 | -0.0233229  | -0.012383   | -0.0397693   | -0.0241736  |  0.0674013   |  0.0322475  |
| 1 - Undecene                                  | -0.0140085  | -0.03863    | -0.534517    |  0.675438   | -0.0160387   | -0.0722431  |
| 1-Butanol                                     |  0.0020607  |  0.0990976  |  0.325793    | -0.0177587  | -0.171591    | -0.237601   |
| 2-Heptanone                                   |  0.180268   |  0.241084   | -0.14815     |  0.0909435  | -0.15043     | -0.213717   |
| Dodecane                                      |  0.00783019 | -0.060622   |  0.426336    | -0.254063   | -0.0313362   | -0.0881447  |
| 1-Butanol, 3-methyl-                          | -0.0532247  | -0.0254416  |  0.0938974   |  0.205947   | -0.658836    |  0.437658   |
| S-Methyl 3-methylbutanethioate                |  0.0403756  |  0.0251114  | -0.136508    | -0.0991984  |  0.119689    |  0.0505301  |
| 2-Heptanone, 4,6-dimethyl-                    |  0.0704913  | -0.0372213  |  0.108922    | -0.00540945 | -0.0190045   | -0.117778   |
| 3-Buten-1-ol, 3-methyl-                       | -0.102898   | -0.13518    | -0.120072    |  0.150604   |  0.0599864   |  0.147559   |
| Thiocyanic acid, methyl ester                 | -0.00795293 | -0.00258273 | -0.247937    |  0.284855   | -0.00314884  | -0.0232334  |
| Acetoin                                       |  0.0382066  | -0.17662    | -0.229179    | -0.00295039 |  0.286094    |  0.0844498  |
| 1-Pentanol, 2-methyl-                         |  0.135433   |  0.0102615  | -0.0531573   | -0.024218   | -0.0223964   | -0.0459224  |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester | -0.0382515  | -0.047399   |  0.227177    |  0.107022   | -0.0477901   | -0.200758   |
| 2-Heptanol, 4-methyl-                         | -0.0134429  | -0.00931455 |  0.190903    | -0.0576315  | -0.0102982   | -0.100216   |
| 2-Nonanone                                    | -0.571481   |  0.197825   | -0.330808    |  0.21383    |  0.283251    |  0.207382   |
| Acetic acid                                   | -0.2574     |  0.149472   |  0.00551176  | -0.0253714  | -0.117721    |  0.245509   |
| 2-Nonanol                                     | -0.0461575  | -0.0854509  |  0.0729014   |  0.341767   | -0.131928    | -0.151132   |
| Pyrrole                                       |  0.0886072  |  0.0708509  | -0.35464     | -0.272722   |  0.215657    |  0.252246   |
| 1H-Pyrrole, 2-methyl-                         | -0.0608753  | -0.0800622  |  0.206095    |  0.242793   | -0.108984    | -0.198967   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.192917   |  0.0712901  | -0.136349    |  0.0283849  | -0.0805784   | -0.0756647  |
| Propanoic acid                                |  0.0294824  |  0.117843   | -0.13179     | -0.028471   | -0.614791    |  0.627726   |
| Propanoic acid, 2-methyl-                     | -0.0183114  | -0.0309534  | -0.0901046   | -0.0200809  |  0.327848    | -0.168398   |
| 1-Octanol                                     |  0.310549   |  0.111105   | -0.102865    | -0.0491749  | -0.20036     | -0.0692539  |
| 2-Undecanone                                  | -0.136287   |  0.169059   |  0.0157148   |  0.444026   | -0.218459    | -0.274054   |
| Benzoic acid, methyl ester                    |  0.27108    |  0.109      |  0.00530207  | -0.128311   | -0.178891    | -0.0781799  |
| Butyrolactone                                 | -0.0565296  | -0.0533283  | -0.139904    | -0.0322235  |  0.380929    | -0.098944   |
| Decanoic acid, ethyl ester                    |  0.0650801  |  0.0324047  | -0.0196541   | -0.00873675 | -0.0472196   | -0.0218743  |
| Acetic acid, decyl ester                      | -0.0764947  |  0.113882   | -0.00371715  | -0.00938858 | -0.00072819  | -0.0235538  |
| 2-Undecanol                                   | -0.0889521  |  0.0478645  |  0.373681    |  0.0715146  | -0.202034    | -0.202074   |
| Butanoic acid, 3-methyl-                      | -0.100453   | -0.0905437  | -0.202627    | -0.0686469  |  0.423616    |  0.0386547  |
| 2-Dodecanone                                  |  0.0789081  |  0.0391224  | -0.0645165   | -0.00514966 | -0.0153354   | -0.0330289  |
| 1-Decanol                                     |  0.0291314  |  0.341193   | -0.100272    | -0.0409068  | -0.166916    | -0.0622303  |
| 2-Tridecanone                                 |  0.00887627 | -0.056349   | -0.00176086  |  0.0124949  |  0.0494953   | -0.0127566  |
| Dodecanoic acid, ethyl ester                  | -0.0257988  |  0.0566312  | -0.00247702  | -0.00715171 | -0.000645187 | -0.0205585  |
| 1,4-Butanediol                                | -0.0464989  | -0.0440644  | -0.11743     | -0.0302477  |  0.076188    |  0.162054   |
| Phenylethyl Alcohol                           |  0.165064   |  0.154317   | -0.0715361   | -0.0489122  | -0.13362     | -0.0653137  |
| Acetophenone, 2'-amino-                       | -0.0416242  | -0.0551983  | -0.283861    |  0.621302   | -0.0998461   | -0.140773   |
| 2-Tridecanol                                  | -0.112461   |  0.245894   | -0.0241238   | -0.0219073  | -0.0262875   | -0.0611145  |
| Tetradecanal                                  |  0.0513046  | -0.0470627  | -0.000947475 | -0.00173706 | -0.000162684 | -0.00139463 |
| 1-Dodecanol                                   |  0.130532   | -0.459379   |  0.107888    |  0.0288935  |  0.0860775   |  0.105988   |
| Methyl tetradecanoate                         | -0.246741   |  0.378606   | -0.0396839   | -0.014023   | -0.0182638   | -0.059894   |
| 2-Pentadecanone                               | -0.102988   |  0.320613   | -0.070281    | -0.014276   | -0.0444031   | -0.0886651  |
| Tetradecanoic acid, ethyl ester               |  0.0145608  |  0.00413354 | -0.00110898  | -0.00483642 | -0.00017022  | -0.0125787  |
| Hexadecanal                                   |  0.19676    |  0.0424093  | -0.0713012   | -0.0248423  | -0.0609139   | -0.0821121  |
| n-Tridecan-1-ol                               | -0.089703   |  0.275672   | -0.082042    | -0.00798267 | -0.0350916   | -0.0608525  |
| 1-Tetradecanol                                |  0.148386   | -0.556462   |  0.123019    |  0.0393888  |  0.130084    |  0.115584   |
| n-Pentadecanol                                |  0.323371   | -0.209931   | -0.0537379   | -0.00447661 | -0.0124283   | -0.042797   |
| 1-Hexadecanol                                 |  0.540818   | -0.0988063  | -0.119256    | -0.0325353  | -0.195977    | -0.0942433  |
| Indole                                        |  0.197618   | -0.00780427 | -0.0378979   | -0.0224284  | -0.124066    | -0.00542174 |


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
