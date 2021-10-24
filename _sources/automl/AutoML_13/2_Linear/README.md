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

20.7 seconds

### Metric details
|           |   0 |   1 |   2 |   3 |   4 |   5 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|----:|----:|----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0616692 |
| recall    |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0616692 |
| f1-score  |   1 |   1 |   1 |   1 |   1 |   1 |          1 |           1 |              1 | 0.0616692 |
| support   |   5 |   5 |   5 |   5 |   5 |   5 |          1 |          30 |             30 | 0.0616692 |


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
|                                               |           0 |            1 |            2 |            3 |            4 |           5 |
|:----------------------------------------------|------------:|-------------:|-------------:|-------------:|-------------:|------------:|
| intercept                                     |  0.0756533  |  0.709654    | -0.150689    | -0.222525    | -0.170621    | -0.241472   |
| Ethyl Acetate                                 | -0.0341228  | -0.0834753   |  0.354872    | -0.157563    | -0.0117313   | -0.0679802  |
| Ethanol                                       | -0.179083   |  0.148717    |  0.412131    | -0.189543    | -0.155769    | -0.036454   |
| Propanoic acid, ethyl ester                   |  0.0907162  |  0.0760352   | -0.0677692   |  0.0808114   | -0.229178    |  0.0493841  |
| 2-Pentanone                                   |  0.0771143  | -0.185508    |  0.0887323   | -0.0988498   |  0.0258064   |  0.092705   |
| Decane                                        | -0.513099   |  0.417384    | -0.0254881   | -0.00620543  | -0.161638    |  0.289046   |
| Methyl Isobutyl Ketone                        | -0.050331   |  0.311531    | -0.0420064   | -0.0260606   |  0.000881542 | -0.194015   |
| Amylene hydrate                               | -0.275924   |  0.272142    |  0.0836506   | -0.00829686  |  0.023189    | -0.094761   |
| Butanoic acid, 2-methyl-, methyl ester        |  0.097121   |  0.0230744   | -0.00230176  | -0.290586    |  0.0311245   |  0.141568   |
| Isobutyl acetate                              |  0.0826558  |  0.0333554   |  0.131782    | -0.149887    | -0.0164546   | -0.0814523  |
| Methyl isovalerate                            | -0.238762   | -0.443429    |  0.0716558   | -0.0345052   |  0.0198014   |  0.625239   |
| 1-Propanol                                    |  0.00742912 | -0.0536284   |  0.449564    |  0.000840792 | -0.421961    |  0.0177559  |
| Methyl thiolacetate                           | -0.63127    |  0.688584    | -0.113477    |  0.114253    | -0.183274    |  0.125184   |
| Butanoic acid, 2-methyl-, ethyl ester         |  0.0730797  |  0.104214    | -0.0539799   | -0.0399915   | -0.050832    | -0.0324904  |
| 2-Hexanone                                    | -0.205375   | -0.395757    |  0.0490966   |  0.156938    |  0.288421    |  0.106676   |
| Ethyl isocyanide                              |  0.0488506  | -0.02801     |  0.0404707   |  0.0503546   | -0.110034    | -0.00163158 |
| 1-Propanol, 2-methyl-                         | -0.349451   |  0.389522    |  0.0227838   |  0.0373515   | -0.0671984   | -0.0330073  |
| 2-Pentanol, 2-methyl-                         |  0.35819    | -0.402611    | -0.0198935   |  0.116668    |  0.0447909   | -0.0971442  |
| 2-Pentanol                                    | -0.082303   | -0.465455    |  0.0643047   |  0.205768    |  0.0385749   |  0.239111   |
| 1-Butanol, 3-methyl-, acetate                 | -0.179213   |  0.351402    | -0.0329343   | -0.0403369   | -0.010055    | -0.0888632  |
| 1 - Undecene                                  |  0.0309862  |  0.143008    |  0.051127    | -0.54        |  0.0347936   |  0.280084   |
| 1-Butanol                                     |  0.0375848  |  0.0839838   |  0.129743    | -0.23301     |  0.0241118   | -0.0424135  |
| 2-Heptanone                                   | -0.0634602  | -0.305123    |  0.215219    | -0.0475441   |  0.216771    | -0.0158621  |
| Dodecane                                      |  0.0250738  | -0.0318644   | -0.106885    |  0.319817    | -0.0818024   | -0.124339   |
| 1-Butanol, 3-methyl-                          | -0.226133   | -0.0864775   | -0.055       |  0.249713    | -0.0651211   |  0.183018   |
| S-Methyl 3-methylbutanethioate                |  0.0106203  | -0.0720976   | -0.00942454  |  0.119033    |  0.000663428 | -0.0487946  |
| 2-Heptanone, 4,6-dimethyl-                    |  0.14934    |  0.0432323   |  0.00717717  | -0.0240191   | -0.0263795   | -0.149351   |
| 3-Buten-1-ol, 3-methyl-                       |  0.0386079  |  0.00535095  | -0.0723227   | -0.260548    | -0.0292364   |  0.318148   |
| Thiocyanic acid, methyl ester                 |  0.144275   |  0.109258    |  0.0276922   | -0.432375    |  0.0650172   |  0.0861328  |
| Acetoin                                       |  0.559653   | -0.11589     |  0.0858028   | -0.174097    | -0.221913    | -0.133555   |
| 1-Pentanol, 2-methyl-                         |  0.113024   |  0.0106426   |  0.0533027   |  0.0793502   | -0.3174      |  0.0610808  |
| Butanoic acid, 3-methyl-, 2-methylbutyl ester |  0.0485876  | -0.0579929   | -0.000187442 | -0.00739964  |  0.00818222  |  0.00881019 |
| 2-Heptanol, 4-methyl-                         |  0.0398507  | -0.0160736   | -0.00391721  |  0.118939    |  0.0165322   | -0.155331   |
| 2-Nonanone                                    | -0.0130136  |  0.021104    | -0.387913    | -0.233054    |  0.213553    |  0.399323   |
| Acetic acid                                   |  0.00629183 |  0.176237    | -0.228263    | -0.00607918  |  0.0581963   | -0.00638253 |
| 2-Nonanol                                     | -0.0204948  |  0.0696477   |  0.0296342   | -0.281161    | -0.00128526  |  0.203659   |
| Pyrrole                                       | -0.0346451  |  0.0608606   | -0.0172587   |  0.0184893   | -0.0111437   | -0.0163023  |
| 1H-Pyrrole, 2-methyl-                         | -0.00682648 |  0.0160314   |  0.00479412  | -0.0330428   | -0.00563636  |  0.0246802  |
| 1-Heptanol, 2,4-dimethyl-,                    |  0.082119   |  0.0540215   |  0.133838    | -0.140824    |  0.0768507   | -0.206005   |
| Propanoic acid                                | -0.718271   |  0.595322    | -0.0853449   | -0.0230526   |  0.250104    | -0.0187567  |
| Propanoic acid, 2-methyl-                     |  0.426907   | -0.803658    |  0.0890856   |  0.152146    |  0.0805329   |  0.0549873  |
| 1-Octanol                                     | -0.00717198 |  0.0437569   | -0.0543707   |  0.0452442   | -0.0224342   | -0.00502422 |
| 2-Undecanone                                  |  0.0619166  |  0.032298    | -0.211287    | -0.283044    | -0.0408955   |  0.441012   |
| Benzoic acid, methyl ester                    |  0.0578846  |  0.170279    |  0.164079    | -0.224788    |  0.147916    | -0.31537    |
| Butyrolactone                                 | -0.463725   | -0.0268975   |  0.151254    |  0.0865853   |  0.102745    |  0.150039   |
| Decanoic acid, ethyl ester                    |  0.0237955  | -0.0312429   | -0.0279376   |  0.028618    |  0.0165008   | -0.00973386 |
| Acetic acid, decyl ester                      |  0.0453069  | -0.00843998  | -0.164064    |  0.0410209   |  0.0928978   | -0.00672132 |
| 2-Undecanol                                   | -0.00480558 | -0.0171164   | -0.164025    | -0.0364002   | -0.0930355   |  0.315383   |
| Butanoic acid, 3-methyl-                      |  0.309313   | -0.135274    | -0.0586311   | -0.0286886   | -0.0505208   | -0.036199   |
| 2-Dodecanone                                  |  0.0655386  |  0.00150024  |  0.0128034   |  0.0247296   | -0.15116     |  0.0465877  |
| 1-Decanol                                     |  0.0197527  |  0.00782698  | -0.242686    |  0.0338173   |  0.199783    | -0.0184942  |
| 2-Tridecanone                                 |  0.0795503  |  0.000715674 | -0.033158    |  0.0335714   | -0.106819    |  0.02614    |
| Dodecanoic acid, ethyl ester                  |  0.0463533  | -0.0112359   | -0.100748    |  0.0382999   |  0.025259    |  0.00207133 |
| 1,4-Butanediol                                | -0.463998   | -0.0280791   |  0.151599    |  0.0870944   |  0.102964    |  0.15042    |
| Phenylethyl Alcohol                           |  0.0188558  |  0.0847685   |  0.0260244   |  0.0864548   | -0.242396    |  0.026293   |
| Acetophenone, 2'-amino-                       |  0.090712   |  0.0559777   |  0.0490229   | -0.377184    |  0.0516839   |  0.129787   |
| 2-Tridecanol                                  |  0.069692   |  0.0106077   | -0.536482    |  0.0433029   |  0.403724    |  0.0091558  |
| Tetradecanal                                  |  0.287092   |  0.276618    | -0.495336    |  0.174958    | -0.410033    |  0.166701   |
| 1-Dodecanol                                   |  0.0220932  |  0.00740488  | -0.0420403   |  0.0275834   | -0.015417    |  0.00037586 |
| Methyl tetradecanoate                         |  0.0599315  | -0.0248937   | -0.285564    |  0.0144073   |  0.240923    | -0.00480374 |
| 2-Pentadecanone                               |  0.0809819  | -0.0265477   | -0.134344    |  0.0179943   |  0.0516204   |  0.0102955  |
| Tetradecanoic acid, ethyl ester               |  0.110444   |  0.0517414   | -0.23942     |  0.0703777   | -0.0332612   |  0.0401181  |
| Hexadecanal                                   |  0.0705617  |  0.0238694   |  0.0267416   |  0.0452311   | -0.187056    |  0.0206518  |
| n-Tridecan-1-ol                               |  0.0843104  | -0.0136016   | -0.112672    |  0.0164022   | -0.0210118   |  0.0465729  |
| 1-Tetradecanol                                |  0.0747049  |  0.0969525   |  0.397225    |  0.064303    | -0.688703    |  0.0555174  |
| n-Pentadecanol                                | -0.00409601 | -0.0229054   |  0.227713    | -0.037471    | -0.148807    | -0.0144339  |
| 1-Hexadecanol                                 |  0.106585   |  0.00863509  |  0.0627459   |  0.00503566  | -0.211496    |  0.0284944  |
| Indole                                        | -0.0657171  |  0.0589891   |  0.193337    | -0.00729495  | -0.168261    | -0.0110526  |


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
