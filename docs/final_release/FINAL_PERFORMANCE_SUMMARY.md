# Final Performance Summary

## Final Optimized ANN

| Metric | Value |
|---|---:|
| Accuracy | 0.847538 |
| Precision | 0.424166 |
| Recall | 0.849937 |
| F1 Score | 0.565911 |
| ROC-AUC | 0.920331 |
| PR-AUC | 0.599071 |

## Confusion Matrix

| | Predicted Negative | Predicted Positive |
|---|---:|---:|
| Actual Negative | 5074 | 915 |
| Actual Positive | 119 | 674 |

## Final Configuration

- Architecture: ANN_Architecture_1_Baseline
- Hidden Layers: [128, 64, 32]
- Learning Rate: 0.0005
- Dropout: 0.3
- Batch Size: 64
- Optimizer: adam
- Input Dimension: 52
- Threshold: 0.5

## Evaluation Integrity

The test set contains 6782 samples.

The test set was protected from retraining and hyperparameter
selection and was used only for final evaluation.

## Release Decision

FINAL MODEL APPROVED FOR RELEASE.
