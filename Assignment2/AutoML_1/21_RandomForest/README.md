# Summary of 21_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.6
- **min_samples_split**: 50
- **max_depth**: 6
- **eval_metric_name**: f1
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

25.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.634902 |  nan        |
| auc       | 0.639883 |  nan        |
| f1        | 0.772302 |    0.496627 |
| accuracy  | 0.656107 |    0.496627 |
| precision | 0.896907 |    0.744532 |
| recall    | 1        |    0.188909 |
| mcc       | 0.233034 |    0.496627 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.634902 |  nan        |
| auc       | 0.639883 |  nan        |
| f1        | 0.772302 |    0.496627 |
| accuracy  | 0.656107 |    0.496627 |
| precision | 0.647732 |    0.496627 |
| recall    | 0.956195 |    0.496627 |
| mcc       | 0.233034 |    0.496627 |


## Confusion matrix (at threshold=0.496627)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              191 |              831 |
| Labeled as 1 |               70 |             1528 |

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
