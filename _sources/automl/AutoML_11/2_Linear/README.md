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

20.3 seconds

### Metric details
|           |        0 |        1 |   2 |        3 |        4 |        5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|---------:|----:|---------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 1        | 0.714286 |   1 | 0.833333 | 1        | 1        |        0.9 |    0.924603 |       0.924603 |   0.34405 |
| recall    | 0.8      | 1        |   1 | 1        | 0.8      | 0.8      |        0.9 |    0.9      |       0.9      |   0.34405 |
| f1-score  | 0.888889 | 0.833333 |   1 | 0.909091 | 0.888889 | 0.888889 |        0.9 |    0.901515 |       0.901515 |   0.34405 |
| support   | 5        | 5        |   5 | 5        | 5        | 5        |        0.9 |   30        |      30        |   0.34405 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |                4 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |                5 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                0 |                0 |                5 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |                5 |                0 |                0 |
| Labeled as 4 |                0 |                1 |                0 |                0 |                4 |                0 |
| Labeled as 5 |                0 |                0 |                0 |                1 |                0 |                4 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|                                               |            0 |            1 |            2 |           3 |            4 |            5 |
|:----------------------------------------------|-------------:|-------------:|-------------:|------------:|-------------:|-------------:|
| intercept                                     |  0.44774     |  0.871007    | -0.279082    | -0.298536   | -0.41323     | -0.327899    |
| Ethyl Acetate                                 |  0.0116549   | -0.511127    |  0.459135    | -0.128632   |  0.148654    |  0.0203149   |
| Ethanol                                       | -0.141076    |  0.0078233   |  0.386215    | -0.159983   | -0.00195983  | -0.0910202   |
| Propanoic acid, ethyl ester                   |  0.0628731   |  0.0747932   |  0.0239574   |  0.0535098  | -0.26002     |  0.0448864   |
| 2-Pentanone                                   |  0.0646222   | -0.167141    |  0.09263     | -0.0122898  |  0.0342882   | -0.0121091   |
| Decane                                        | -0.101043    |  0.0873972   | -0.0882076   |  0.138669   | -0.142648    |  0.105832    |
| Methyl Isobutyl Ketone                        | -0.26352     |  0.507646    |  0.0130367   | -0.0784552  |  0.0311981   | -0.209906    |
| Amylene hydrate                               | -0.362905    |  0.25652     |  0.0237445   |  0.0848941  |  0.172276    | -0.17453     |
| Butanoic acid, 2-methyl-, methyl ester        |  0.0405756   |  0.0917507   | -0.0128092   | -0.296721   | -0.000606107 |  0.17781     |
| Isobutyl acetate                              |  0.0622799   |  0.0250753   |  0.0451582   | -0.264874   | -0.00133518  |  0.133696    |
| Methyl isovalerate                            | -0.186351    | -0.652356    |  0.0965803   |  0.126596   |  0.0836196   |  0.531911    |
| 1-Propanol                                    | -0.0026842   | -0.0219512   |  0.475742    | -0.0131815  | -0.457984    |  0.020059    |
| Methyl thiolacetate                           | -0.273016    |  0.461995    | -0.188203    |  0.199753   | -0.301989    |  0.10146     |
| Butanoic acid, 2-methyl-, ethyl ester         |  0.318538    | -0.387866    |  0.0546711   |  0.00261404 | -0.0381691   |  0.0502125   |
| 2-Hexanone                                    | -0.796513    | -0.0835347   |  0.152909    |  0.150728   |  0.425332    |  0.151079    |
| Ethyl isocyanide                              |  0.0977834   |  0.102437    | -0.163788    |  0.0684748  | -0.146949    |  0.0420408   |
| 1-Propanol, 2-methyl-                         |  0.0715241   |  0.288197    | -0.108368    | -0.05635    |  0.0165957   | -0.211598    |
| 2-Pentanol, 2-methyl-                         | -0.067287    | -0.0822873   | -0.068869    |  0.334331   |  0.0568765   | -0.172764    |
| 2-Pentanol                                    | -0.252436    | -0.697213    |  0.163281    |  0.330152   |  0.12798     |  0.328237    |
| 1-Butanol, 3-methyl-, acetate                 | -0.315212    |  0.302233    | -0.0217099   |  0.026255   |  0.0562538   | -0.04782     |
| 1 - Undecene                                  | -0.00585784  |  0.0566589   |  0.0310995   | -0.621296   |  0.0152296   |  0.524166    |
| 1-Butanol                                     |  0.0661456   |  0.178932    |  0.157296    | -0.119323   | -0.0674554   | -0.215595    |
| 2-Heptanone                                   | -0.267705    | -0.469835    |  0.39522     |  0.0261219  |  0.341213    | -0.0250145   |
| Dodecane                                      |  0.0397162   | -0.0522816   | -0.0392203   |  0.345495   | -0.129228    | -0.164481    |
| 1-Butanol, 3-methyl-                          | -0.799604    |  0.281993    | -0.104834    |  0.374908   | -0.0967071   |  0.344244    |
| S-Methyl 3-methylbutanethioate                |  0.103089    | -0.0307062   |  0.0102921   |  0.0973632  |  0.0255966   | -0.205634    |
| 2-Heptanone, 4,6-dimethyl-                    |  0.211708    |  0.0848495   | -0.283882    |  0.112547   |  0.0449322   | -0.170154    |
| 3-Buten-1-ol, 3-methyl-                       |  0.221051    | -0.22219     | -0.0328715   | -0.218909   | -0.110933    |  0.363852    |
| Thiocyanic acid, methyl ester                 |  0.141035    |  0.26177     |  0.0309805   | -0.592266   |  0.0483059   |  0.110175    |
| Acetoin                                       |  0.509621    |  0.0214537   | -0.118699    | -0.157359   | -0.118648    | -0.13637     |
| 1-Pentanol, 2-methyl-                         |  0.147672    |  0.108313    | -0.1597      |  0.0824228  | -0.259014    |  0.0803059   |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester |  0.106365    | -0.00462628  |  0.0241556   | -0.0704651  |  0.0352794   | -0.0907087   |
| 2-Heptanol, 4-methyl-                         |  0.145152    | -0.0839738   |  0.0349787   | -0.0267947  |  0.0278694   | -0.0972316   |
| 2-Nonanone                                    | -0.00700923  |  0.131943    | -0.37586     | -0.259731   |  0.0527122   |  0.457945    |
| Acetic acid                                   | -0.194603    |  0.422389    | -0.319099    | -0.0195927  |  0.0628115   |  0.0480933   |
| 2-Nonanol                                     | -0.00393685  | -0.000390465 |  0.027368    | -0.341756   |  0.0155971   |  0.303118    |
| Pyrrole                                       |  0.0360335   | -0.00350617  | -0.0348174   |  0.235091   | -0.0226985   | -0.210103    |
| 1H-Pyrrole, 2-methyl-                         |  0.0678368   |  0.0127488   |  0.00750616  | -0.0538775  |  0.00716145  | -0.0413758   |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.0402565   |  0.0752685   |  0.254346    | -0.324781   |  0.190665    | -0.235755    |
| Propanoic acid                                | -1.08899     |  0.801479    | -0.000954358 | -0.0195085  |  0.283502    |  0.0244683   |
| Propanoic acid, 2-methyl-                     |  0.249363    | -0.128288    | -0.0151925   | -0.0536336  | -0.010692    | -0.0415568   |
| 1-Octanol                                     |  0.050405    |  0.133311    |  0.0559865   |  0.060432   | -0.320141    |  0.0200061   |
| 2-Undecanone                                  |  0.0698055   |  0.0502594   | -0.163519    | -0.232125   | -0.125592    |  0.401172    |
| Benzoic acid, methyl ester                    |  0.119274    |  0.248935    |  0.295922    | -0.361254   |  0.0625274   | -0.365405    |
| Butyrolactone                                 |  0.266583    | -0.323937    |  0.0145161   |  0.00435565 |  0.00447136  |  0.0340111   |
| Decanoic acid, ethyl ester                    |  0.00264799  | -0.0440245   | -0.00880783  |  0.0168751  |  0.0470622   | -0.0137529   |
| Acetic acid, decyl ester                      |  0.03289     |  0.000195355 | -0.0801986   |  0.0332526  |  0.0130791   |  0.000781558 |
| 2-Undecanol                                   |  0.0931175   |  0.0343832   | -0.207876    |  0.0225123  | -0.118629    |  0.176492    |
| Butanoic acid, 3-methyl-                      |  0.462453    | -0.41966     |  0.0318553   | -0.0184333  | -0.104809    |  0.0485939   |
| 2-Dodecanone                                  |  0.0432008   | -0.108659    |  0.109147    | -0.0284689  | -0.0229505   |  0.00772986  |
| 1-Decanol                                     |  0.085668    |  0.0403148   | -0.194969    |  0.0446225  |  0.0110487   |  0.0133154   |
| 2-Tridecanone                                 |  0.0730232   | -0.088624    |  0.0578522   |  0.00365748 | -0.0602225   |  0.0143136   |
| Dodecanoic acid, ethyl ester                  |  0.000497793 | -0.037337    | -0.0246236   |  0.0201582  |  0.0496035   | -0.00829883  |
| 1,4-Butanediol                                |  0.162152    | -0.146825    |  0.000687495 | -0.0206195  | -0.0122277   |  0.0168319   |
| Phenylethyl Alcohol                           |  0.0725318   |  0.157358    | -0.119026    |  0.08246    | -0.245263    |  0.0519388   |
| Acetophenone, 2'-amino-                       |  0.043859    |  0.00355405  |  0.0282363   | -0.449609   |  0.0137106   |  0.360249    |
| 2-Tridecanol                                  |  0.163204    |  0.00829688  | -0.372133    |  0.0333893  |  0.159055    |  0.00818786  |
| Tetradecanal                                  | -0.0205262   |  0.028629    |  0.0857043   |  0.0286557  | -0.142057    |  0.0195939   |
| 1-Dodecanol                                   |  0.0394969   |  0.0159882   |  0.0209158   |  0.0310176  | -0.11487     |  0.00745153  |
| Methyl tetradecanoate                         |  0.0860191   | -0.086044    | -0.274486    |  0.0136853  |  0.258936    |  0.00188893  |
| 2-Pentadecanone                               |  0.115873    | -0.126768    | -0.11076     | -0.00122696 |  0.123386    | -0.0005031   |
| Tetradecanoic acid, ethyl ester               | -0.00389607  | -0.011263    |  0.0162974   |  0.0277553  | -0.0294812   |  0.000587597 |
| Hexadecanal                                   | -0.0411478   | -0.00481739  |  0.267109    | -0.0112814  | -0.209626    | -0.000237064 |
| n-Tridecan-1-ol                               |  0.0528205   | -0.150025    | -0.0758982   | -0.0212744  |  0.184511    |  0.00986594  |
| 1-Tetradecanol                                |  0.0196652   |  0.065905    |  0.363238    |  0.0305369  | -0.504032    |  0.0246875   |
| n-Pentadecanol                                |  0.0394047   | -0.0295762   |  0.248614    | -0.0492791  | -0.199486    | -0.00967776  |
| 1-Hexadecanol                                 |  0.0734295   | -0.00435076  |  0.257821    |  0.00726194 | -0.356961    |  0.0227995   |
| Indole                                        | -0.0886515   |  0.119762    |  0.467529    |  0.0110385  | -0.546805    |  0.0371273   |


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
