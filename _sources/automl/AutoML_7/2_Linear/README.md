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

27.4 seconds

### Metric details
|           |     EC_A |     EC_B |     PA_A |   PA_B |   SA_A |   SA_B |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|---------:|-------:|-------:|-------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.625    | 0.625    |      0 |      1 |      1 |        0.8 |    0.708333 |       0.708333 |  0.763105 |
| recall    | 0.8      | 1        | 1        |      0 |      1 |      1 |        0.8 |    0.8      |       0.8      |  0.763105 |
| f1-score  | 0.888889 | 0.769231 | 0.769231 |      0 |      1 |      1 |        0.8 |    0.737892 |       0.737892 |  0.763105 |
| support   | 5        | 5        | 5        |      5 |      5 |      5 |        0.8 |   30        |      30        |  0.763105 |


## Confusion matrix
|                 |   Predicted as EC_A |   Predicted as EC_B |   Predicted as PA_A |   Predicted as PA_B |   Predicted as SA_A |   Predicted as SA_B |
|:----------------|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|
| Labeled as EC_A |                   4 |                   1 |                   0 |                   0 |                   0 |                   0 |
| Labeled as EC_B |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |
| Labeled as PA_A |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |
| Labeled as PA_B |                   0 |                   2 |                   3 |                   0 |                   0 |                   0 |
| Labeled as SA_A |                   0 |                   0 |                   0 |                   0 |                   5 |                   0 |
| Labeled as SA_B |                   0 |                   0 |                   0 |                   0 |                   0 |                   5 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |        EC_A |        EC_B |        PA_A |        PA_B |         SA_A |        SA_B |
|:----------------------------------------------|------------:|------------:|------------:|------------:|-------------:|------------:|
| intercept                                     | -0.110792   | -0.0675465  |  0.202295   | -0.188713   | -0.211626    |  0.376382   |
| Ethyl Acetate                                 |  0.26413    | -0.00224999 | -0.270175   |  0.0340124  | -0.132051    |  0.106334   |
| Ethanol                                       |  0.191939   | -0.00210817 | -0.290638   | -0.00948911 |  0.186581    | -0.0762844  |
| Propanoic acid, ethyl ester                   |  0.105778   | -0.0723732  | -0.0113986  | -0.0053267  | -0.00131754  | -0.0153618  |
| 2-Pentanone                                   | -0.0857014  |  0.011435   |  0.00550147 |  0.0235026  |  0.42522     | -0.379958   |
| Decane                                        | -0.0815922  | -0.160078   |  0.135618   |  0.179213   | -0.455237    |  0.382075   |
| Methyl Isobutyl Ketone                        | -0.0591602  | -0.0564204  | -0.0672063  | -0.0330519  | -0.0225281   |  0.238367   |
| Amylene hydrate                               | -0.0898088  |  0.0464713  |  0.0687273  | -0.0481629  | -0.580572    |  0.603345   |
| Butanoic acid, 2-methyl-, methyl ester        | -0.0385378  | -0.0423954  |  0.00426152 |  0.256568   | -0.0635605   | -0.116335   |
| Isobutyl acetate                              |  0.0560342  |  0.0167313  | -0.0755644  |  0.0536224  | -0.0152814   | -0.0355421  |
| Methyl isovalerate                            | -0.0582677  | -0.0685783  |  0.0589621  |  0.319052   | -0.0984036   | -0.152765   |
| 1-Propanol                                    |  0.465974   | -0.133235   | -0.0895158  | -0.0309321  | -0.162148    | -0.050144   |
| Methyl thiolacetate                           | -0.12015    | -0.12307    |  0.143051   |  0.106198   | -0.599068    |  0.593039   |
| Butanoic acid, 2-methyl-, ethyl ester         | -0.153891   | -0.140979   | -0.233953   | -0.119326   |  0.466833    |  0.181316   |
| 2-Hexanone                                    | -0.0948365  |  0.272533   | -0.0568131  | -0.0463862  | -0.0375649   | -0.0369327  |
| Ethyl isocyanide                              | -0.0252797  |  0.101331   | -0.0150162  | -0.0111257  | -0.00152078  | -0.0483888  |
| 1-Propanol, 2-methyl-                         | -0.111042   | -0.0842646  | -0.0472153  | -0.069741   | -0.101321    |  0.413583   |
| 2-Pentanol, 2-methyl-                         | -0.0261886  | -0.0107132  |  0.294182   | -0.281075   |  0.155314    | -0.13152    |
| 2-Pentanol                                    | -0.0712336  | -0.0983602  |  0.310895   |  0.135385   |  0.116639    | -0.393325   |
| 1-Butanol, 3-methyl-, acetate                 | -0.0325274  | -0.0196035  | -0.0333644  | -0.0444176  | -0.13171     |  0.261623   |
| 1 - Undecene                                  |  0.0574294  |  0.0413758  | -0.731405   |  0.387716   |  0.165875    |  0.0790095  |
| 1-Butanol                                     |  0.109176   |  0.0672829  |  0.34737    | -0.135465   | -0.193075    | -0.195288   |
| 2-Heptanone                                   |  0.0247265  |  0.414816   | -0.100295   |  0.0121755  | -0.162983    | -0.18844    |
| Dodecane                                      |  0.0468152  | -0.0616669  |  0.283144   | -0.210261   | -0.0180669   | -0.0399641  |
| 1-Butanol, 3-methyl-                          |  0.0015663  | -0.0532313  | -0.168741   |  0.309702   | -0.700189    |  0.610893   |
| S-Methyl 3-methylbutanethioate                | -0.0557869  | -0.0664321  |  0.295739   | -0.00107894 | -0.0617356   | -0.110706   |
| 2-Heptanone, 4,6-dimethyl-                    | -0.0443683  |  0.0486767  |  0.234762   | -0.0547562  | -0.030444    | -0.15387    |
| 3-Buten-1-ol, 3-methyl-                       | -0.138182   | -0.0969621  | -0.153061   |  0.144363   |  0.133365    |  0.110477   |
| Thiocyanic acid, methyl ester                 | -0.0173478  | -0.0169056  | -0.277082   |  0.423664   | -0.0468666   | -0.0654623  |
| Acetoin                                       |  0.0987583  | -0.208275   | -0.223906   | -0.0874445  |  0.486871    | -0.0660031  |
| 1-Pentanol, 2-methyl-                         |  0.109407   |  0.00981482 | -0.0495203  | -0.0226119  | -0.0166004   | -0.0304889  |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester | -0.0275703  | -0.0429423  | -0.0508518  |  0.2616     | -0.0295129   | -0.110723   |
| 2-Heptanol, 4-methyl-                         | -0.00841294 | -0.0113469  |  0.105039   | -0.0257143  | -0.00667808  | -0.0528865  |
| 2-Nonanone                                    | -0.454616   |  0.194569   | -0.353633   |  0.221417   |  0.264157    |  0.128106   |
| Acetic acid                                   | -0.216825   | -0.0489816  |  0.279559   |  0.128423   | -0.128505    | -0.0136714  |
| 2-Nonanol                                     | -0.053653   | -0.112095   |  0.0181041  |  0.422339   | -0.128782    | -0.145913   |
| Pyrrole                                       | -0.00357239 | -0.0185202  |  0.0444825  | -0.0734021  |  0.104697    | -0.0536844  |
| 1H-Pyrrole, 2-methyl-                         | -0.0482347  | -0.0645873  |  0.223315   |  0.0879503  | -0.0647411   | -0.133702   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.146123   |  0.102416   | -0.0650936  | -0.0439787  | -0.0759256   | -0.0635405  |
| Propanoic acid                                | -0.0941187  |  0.158586   | -0.167991   | -0.0629833  | -0.626689    |  0.793196   |
| Propanoic acid, 2-methyl-                     | -0.0486247  | -0.0570125  | -0.0936063  | -0.0699328  |  0.337127    | -0.0679509  |
| 1-Octanol                                     |  0.360235   |  0.174476   | -0.114712   | -0.058662   | -0.283532    | -0.0778047  |
| 2-Undecanone                                  | -0.0548171  |  0.174733   |  0.0301124  |  0.401424   | -0.289732    | -0.261721   |
| Benzoic acid, methyl ester                    |  0.199035   |  0.185104   | -0.07045    | -0.0739915  | -0.165467    | -0.0742305  |
| Butyrolactone                                 | -0.0364434  | -0.04898    | -0.0776105  | -0.0342828  |  0.344701    | -0.147384   |
| Decanoic acid, ethyl ester                    |  0.0166116  |  0.0456127  | -0.0150243  | -0.013664   | -0.00223795  | -0.031298   |
| Acetic acid, decyl ester                      | -0.0526669  |  0.123386   | -0.0124581  | -0.0150912  | -0.00191055  | -0.0412591  |
| 2-Undecanol                                   | -0.0399636  |  0.0866866  |  0.256218   |  0.114518   | -0.248514    | -0.168945   |
| Butanoic acid, 3-methyl-                      |  0.128091   |  0.111806   |  0.168791   |  0.10305    |  0.103066    | -0.614804   |
| 2-Dodecanone                                  |  0.184213   | -0.0729803  | -0.0558636  | -0.00539407 | -0.0149044   | -0.0350708  |
| 1-Decanol                                     | -0.093712   | -0.109522   |  0.0696403  |  0.00394777 |  0.0731836   |  0.0564627  |
| 2-Tridecanone                                 |  0.110805   |  0.0324666  | -0.0529928  | -0.0136514  | -0.0112713   | -0.0653561  |
| Dodecanoic acid, ethyl ester                  | -0.0117683  |  0.0603714  | -0.00951111 | -0.012249   | -0.00160125  | -0.0252418  |
| 1,4-Butanediol                                | -0.0310327  | -0.0418483  | -0.0674806  | -0.0341374  |  2.29743e-05 |  0.174476   |
| Phenylethyl Alcohol                           |  0.253768   |  0.154818   | -0.0793613  | -0.0547301  | -0.204595    | -0.0698988  |
| Acetophenone, 2'-amino-                       | -0.0440375  | -0.082393   | -0.300415   |  0.664413   | -0.120544    | -0.117023   |
| 2-Tridecanol                                  | -0.118739   |  0.301805   | -0.0342906  | -0.0311594  | -0.0445285   | -0.0730874  |
| Tetradecanal                                  |  0.063684   | -0.0522661  | -0.00384492 | -0.00332344 | -0.000458259 | -0.00379123 |
| 1-Dodecanol                                   |  0.177793   | -0.353567   |  0.0588803  |  0.0235126  |  0.0599036   |  0.0334776  |
| Methyl tetradecanoate                         | -0.170171   |  0.326203   | -0.0453552  | -0.0219698  | -0.0174544   | -0.0712518  |
| 2-Pentadecanone                               | -0.0343549  |  0.218308   | -0.0563886  | -0.0221196  | -0.0294563   | -0.0759889  |
| Tetradecanoic acid, ethyl ester               |  0.030396   | -0.0100129  | -0.0033064  | -0.00493927 | -0.000350779 | -0.0117867  |
| Hexadecanal                                   |  0.173456   |  0.0140931  | -0.0595666  | -0.0160359  | -0.0426549   | -0.0692923  |
| n-Tridecan-1-ol                               |  0.0280595  |  0.144594   | -0.0781743  | -0.00857777 | -0.0314227   | -0.0544787  |
| 1-Tetradecanol                                |  0.268169   | -0.605909   |  0.092004   |  0.0504506  |  0.134685    |  0.0606008  |
| n-Pentadecanol                                |  0.219548   | -0.115482   | -0.0496981  | -0.00530149 | -0.0144466   | -0.0346194  |
| 1-Hexadecanol                                 |  0.461834   | -0.0468789  | -0.0972693  | -0.0338857  | -0.198784    | -0.0850159  |
| Indole                                        |  0.139711   | -0.0837767  |  0.00479184 | -0.00211327 | -0.0901341   |  0.0315216  |


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
