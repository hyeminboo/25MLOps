# Summary of 3_Default_CatBoost_GoldenFeatures

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 6
- **rsm**: 1
- **loss_function**: Logloss
- **eval_metric**: F1
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True
 - **random_seed**: 1234

## Optimized metric
f1

## Training time

8.0 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.633482 |  nan        |
| auc       | 0.658368 |  nan        |
| f1        | 0.778428 |    0.50374  |
| accuracy  | 0.667557 |    0.50374  |
| precision | 0.910569 |    0.721943 |
| recall    | 1        |    0.16212  |
| mcc       | 0.268206 |    0.50374  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.633482 |   nan       |
| auc       | 0.658368 |   nan       |
| f1        | 0.778428 |     0.50374 |
| accuracy  | 0.667557 |     0.50374 |
| precision | 0.655808 |     0.50374 |
| recall    | 0.957447 |     0.50374 |
| mcc       | 0.268206 |     0.50374 |


## Confusion matrix (at threshold=0.50374)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              219 |              803 |
| Labeled as 1 |               68 |             1530 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
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
