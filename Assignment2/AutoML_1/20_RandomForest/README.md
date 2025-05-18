# Summary of 20_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 40
- **max_depth**: 3
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

13.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.647349 |  nan        |
| auc       | 0.607389 |  nan        |
| f1        | 0.771265 |    0.500094 |
| accuracy  | 0.65     |    0.500094 |
| precision | 0.789116 |    0.693765 |
| recall    | 1        |    0.199007 |
| mcc       | 0.217978 |    0.500094 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.647349 |  nan        |
| auc       | 0.607389 |  nan        |
| f1        | 0.771265 |    0.500094 |
| accuracy  | 0.65     |    0.500094 |
| precision | 0.641228 |    0.500094 |
| recall    | 0.967459 |    0.500094 |
| mcc       | 0.217978 |    0.500094 |


## Confusion matrix (at threshold=0.500094)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              157 |              865 |
| Labeled as 1 |               52 |             1546 |

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
