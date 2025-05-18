# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model              |   Weight |
|:-------------------|---------:|
| 14_CatBoost        |       14 |
| 16_CatBoost        |        1 |
| 17_CatBoost        |        1 |
| 26_CatBoost        |        4 |
| 28_CatBoost        |        1 |
| 29_CatBoost        |        5 |
| 36_Xgboost         |        1 |
| 38_LightGBM        |        1 |
| 3_Default_CatBoost |        1 |
| 6_Xgboost          |        1 |
| 7_Xgboost          |        1 |

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.621683 |  nan        |
| auc       | 0.689992 |  nan        |
| f1        | 0.787316 |    0.504947 |
| accuracy  | 0.685878 |    0.527582 |
| precision | 0.888889 |    0.784479 |
| recall    | 1        |    0.153349 |
| mcc       | 0.316526 |    0.504947 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.621683 |  nan        |
| auc       | 0.689992 |  nan        |
| f1        | 0.781987 |    0.527582 |
| accuracy  | 0.685878 |    0.527582 |
| precision | 0.677997 |    0.527582 |
| recall    | 0.923655 |    0.527582 |
| mcc       | 0.309381 |    0.527582 |


## Confusion matrix (at threshold=0.527582)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              321 |              701 |
| Labeled as 1 |              122 |             1476 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
