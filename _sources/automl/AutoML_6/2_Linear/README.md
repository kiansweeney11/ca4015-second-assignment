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
|           |     EC_A |   EC_B |     PA_A |   PA_B |     SA_A |   SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|-------:|---------:|-------:|---------:|-------:|-----------:|------------:|---------------:|----------:|
| precision | 1        |      1 | 0.333333 |      0 | 0.625    |      0 |   0.566667 |    0.493056 |       0.493056 |    1.5819 |
| recall    | 0.4      |      1 | 1        |      0 | 1        |      0 |   0.566667 |    0.566667 |       0.566667 |    1.5819 |
| f1-score  | 0.571429 |      1 | 0.5      |      0 | 0.769231 |      0 |   0.566667 |    0.473443 |       0.473443 |    1.5819 |
| support   | 5        |      5 | 5        |      5 | 5        |      5 |   0.566667 |   30        |      30        |    1.5819 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   2 |                   0 |                   3 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   2 |                   0 |                   3 |                   0 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |        EC_A |        EC_B |        PA_A |        PA_B |         SA_A |        SA_B |
|:----------------------------------------------|------------:|------------:|------------:|------------:|-------------:|------------:|
| intercept                                     | -0.146965   |  0.0907813  |  0.118799   | -0.124344   | -0.168805    |  0.230533   |
| Ethyl Acetate                                 |  0.113185   | -0.019245   | -0.268288   |  0.171261   |  0.128195    | -0.125109   |
| Ethanol                                       |  0.205584   | -0.0678451  | -0.267183   |  0.101104   |  0.0867813   | -0.0584417  |
| Propanoic acid, ethyl ester                   |  0.0746938  | -0.0643824  | -0.00136923 | -0.00483601 | -0.000222618 | -0.00388355 |
| 2-Pentanone                                   | -0.0131198  | -0.0480583  | -0.15849    |  0.15654    |  0.323345    | -0.260217   |
| Decane                                        |  0.069334   | -0.211429   |  0.0846027  |  0.12085    | -0.576802    |  0.513444   |
| Methyl Isobutyl Ketone                        | -0.0419607  | -0.0573802  | -0.123514   |  0.00645925 | -0.0667442   |  0.283139   |
| Amylene hydrate                               | -0.0424012  |  0.0376911  |  0.184857   | -0.0827219  | -0.281649    |  0.184224   |
| Butanoic acid, 2-methyl-, methyl ester        | -0.0278826  | -0.0483639  |  0.224657   | -0.0100229  | -0.0285574   | -0.10983    |
| Isobutyl acetate                              |  0.143564   | -0.0598999  | -0.143886   |  0.149392   | -0.046569    | -0.042601   |
| Methyl isovalerate                            | -0.0479904  | -0.0794974  |  0.0507257  |  0.326425   | -0.113581    | -0.136082   |
| 1-Propanol                                    |  0.485858   | -0.200222   | -0.0926795  | -0.0437272  | -0.102162    | -0.0470668  |
| Methyl thiolacetate                           | -0.123245   | -0.112923   |  0.118228   |  0.10793    | -0.753678    |  0.763688   |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.0846623  | -0.112281   | -0.16163    | -0.086263   |  0.104247    |  0.340588   |
| 2-Hexanone                                    | -0.0115867  |  0.207423   | -0.0600736  | -0.0568247  | -0.0407947   | -0.038143   |
| Ethyl isocyanide                              |  0.0411583  |  0.00376363 | -0.00727986 | -0.0153444  | -0.000882007 | -0.0214157  |
| 1-Propanol, 2-methyl-                         | -0.0807547  | -0.118351   |  0.125967   | -0.18991    |  0.0715719   |  0.191477   |
| 2-Pentanol, 2-methyl-                         | -0.0572769  |  0.0238969  |  0.235285   | -0.166703   |  0.296951    | -0.332153   |
| 2-Pentanol                                    | -0.063383   | -0.0988887  |  0.302109   |  0.0749893  |  0.168954    | -0.38378    |
| 1-Butanol, 3-methyl-, acetate                 | -0.0160431  | -0.0131639  | -0.026536   | -0.0261125  | -0.0870148   |  0.16887    |
| 1 - Undecene                                  |  0.0534219  |  0.0465477  | -0.746331   |  0.401793   |  0.155173    |  0.0893957  |
| 1-Butanol                                     |  0.0746097  |  0.0881776  |  0.168472   |  0.0795953  | -0.209739    | -0.201116   |
| 2-Heptanone                                   |  0.0734006  |  0.351169   | -0.0625485  |  0.0250355  | -0.184242    | -0.202815   |
| Dodecane                                      |  0.055971   | -0.0908587  |  0.428987   | -0.294859   | -0.0516852   | -0.0475561  |
| 1-Butanol, 3-methyl-                          | -0.0718252  | -0.045763   |  0.0721397  |  0.274034   | -0.585909    |  0.357323   |
| S-Methyl 3-methylbutanethioate                | -0.017519   | -0.022566   |  0.092517   |  0.0242666  | -0.0281332   | -0.0485655  |
| 2-Heptanone, 4,6-dimethyl-                    |  0.0362277  | -0.0344978  |  0.24879    | -0.058996   | -0.0569576   | -0.134566   |
| 3-Buten-1-ol, 3-methyl-                       | -0.0912018  | -0.169627   | -0.170779   |  0.209816   | -0.15183     |  0.373621   |
| Thiocyanic acid, methyl ester                 | -0.0112816  | -0.00774491 | -0.246384   |  0.307619   | -0.0107161   | -0.0314924  |
| Acetoin                                       |  0.0965062  | -0.24197    | -0.143197   | -0.086371   |  0.0949654   |  0.280066   |
| 1-Pentanol, 2-methyl-                         |  0.203772   | -0.0357604  | -0.0638888  | -0.0380823  | -0.03765     | -0.0283908  |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester | -0.0345433  | -0.0483062  |  0.129093   |  0.153094   | -0.0593238   | -0.140014   |
| 2-Heptanol, 4-methyl-                         | -0.00706644 | -0.0126919  |  0.165062   | -0.105115   | -0.0100164   | -0.0301719  |
| 2-Nonanone                                    | -0.483498   |  0.0688345  | -0.367702   |  0.103182   |  0.456476    |  0.222707   |
| Acetic acid                                   | -0.191552   |  0.111443   |  0.0518086  | -0.0218765  | -0.0650308   |  0.115207   |
| 2-Nonanol                                     | -0.051812   | -0.11454    |  0.0949384  |  0.357084   | -0.165055    | -0.120616   |
| Pyrrole                                       |  0.0335922  |  0.0523142  | -0.072472   | -0.246968   |  0.112532    |  0.121001   |
| 1H-Pyrrole, 2-methyl-                         | -0.0680038  | -0.0975031  |  0.210223   |  0.273912   | -0.169099    | -0.149529   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.0939426  |  0.179989   | -0.140646   |  0.00535085 | -0.0932863   | -0.0453496  |
| Propanoic acid                                |  0.075879   |  0.164785   | -0.159551   | -0.0544678  | -0.495592    |  0.468947   |
| Propanoic acid, 2-methyl-                     | -0.0146446  | -0.00907035 | -0.0105537  | -0.0299685  |  0.440433    | -0.376196   |
| 1-Octanol                                     |  0.265779   |  0.141912   | -0.0844746  | -0.068066   | -0.204536    | -0.0506148  |
| 2-Undecanone                                  | -0.111886   |  0.222475   | -0.0423773  |  0.478384   | -0.282533    | -0.264063   |
| Benzoic acid, methyl ester                    |  0.191854   |  0.167503   |  0.0277658  | -0.171352   | -0.16542     | -0.0503509  |
| Butyrolactone                                 | -0.0393757  | -0.0780617  | -0.118445   | -0.0476589  |  0.246892    |  0.036649   |
| Decanoic acid, ethyl ester                    |  0.0242995  |  0.0353915  | -0.00935283 | -0.0123249  | -0.0209879   | -0.0170255  |
| Acetic acid, decyl ester                      | -0.0565767  |  0.0943672  | -0.00400011 | -0.0141447  | -0.00178808  | -0.0178576  |
| 2-Undecanol                                   | -0.099596   |  0.0740082  |  0.236185   |  0.161857   | -0.225212    | -0.147242   |
| Butanoic acid, 3-methyl-                      | -0.00573347 | -0.0118907  | -0.00642369 | -0.0173032  |  0.0682417   | -0.0268907  |
| 2-Dodecanone                                  |  0.145467   |  0.0255763  | -0.0862793  | -0.0129394  | -0.0405787   | -0.0312455  |
| 1-Decanol                                     |  0.0257046  |  0.221509   | -0.0462164  | -0.0589852  | -0.117814    | -0.0241981  |
| 2-Tridecanone                                 | -0.133498   | -0.260455   |  0.0652858  |  0.0649241  |  0.221599    |  0.0421437  |
| Dodecanoic acid, ethyl ester                  | -0.00800973 |  0.0399399  | -0.00298805 | -0.0108143  | -0.00118928  | -0.0169386  |
| 1,4-Butanediol                                | -0.0274056  | -0.0529532  | -0.0945878  | -0.0433586  | -0.12978     |  0.348085   |
| Phenylethyl Alcohol                           |  0.148484   |  0.173664   | -0.0593231  | -0.0670116  | -0.150758    | -0.0450561  |
| Acetophenone, 2'-amino-                       | -0.0369877  | -0.0859381  | -0.250861   |  0.598258   | -0.102532    | -0.121939   |
| 2-Tridecanol                                  | -0.117188   |  0.301206   | -0.0298314  | -0.0326705  | -0.0728107   | -0.0487055  |
| Tetradecanal                                  |  0.0767243  | -0.0641716  | -0.00204929 | -0.00619414 | -0.000310484 | -0.00399875 |
| 1-Dodecanol                                   |  0.31134    | -0.095308   | -0.0420145  | -0.0283763  | -0.122244    | -0.0233978  |
| Methyl tetradecanoate                         | -0.248865   |  0.433769   | -0.0589374  | -0.0231394  | -0.0580367   | -0.0447907  |
| 2-Pentadecanone                               | -0.0708864  |  0.357275   | -0.0889175  | -0.0271092  | -0.102272    | -0.0680892  |
| Tetradecanoic acid, ethyl ester               |  0.0510447  | -0.0315477  | -0.00175284 | -0.00770474 | -0.000269402 | -0.00977002 |
| Hexadecanal                                   |  0.138429   |  0.103612   | -0.0735455  | -0.0224536  | -0.0864449   | -0.0595966  |
| n-Tridecan-1-ol                               | -0.0581598  |  0.352309   | -0.120435   | -0.0199096  | -0.102324    | -0.0514809  |
| 1-Tetradecanol                                |  0.328068   | -0.563691   |  0.0619844  |  0.0451276  |  0.0860903   |  0.04242    |
| n-Pentadecanol                                |  0.350735   | -0.199862   | -0.0686233  | -0.0117759  | -0.0336252   | -0.0368494  |
| 1-Hexadecanol                                 |  0.473504   | -0.087286   | -0.10106    | -0.0382362  | -0.17745     | -0.0694721  |
| Indole                                        |  0.167116   |  0.0167084  | -0.0219557  | -0.026983   | -0.126349    | -0.00853661 |


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
