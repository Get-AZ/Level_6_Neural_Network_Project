![Level 6 Neural Network Project](./Level%206.png?raw=true)

# Level 6 — Neural Network Project

## Bank Marketing Customer Subscription Prediction

An end-to-end neural network binary classification project using the Bank Marketing dataset.

## Project Overview

This project demonstrates a complete machine learning workflow:

- Data preprocessing
- Feature transformation
- Neural network modeling
- Hyperparameter optimization
- Model selection
- Validation and evaluation
- Threshold analysis
- Model artifact preservation
- Reproducible release packaging

## Dataset

The project uses the Bank Marketing dataset.

- Rows: 45,211
- Original columns: 17
- Numerical features: 7
- Categorical features: 9
- Binary target variable

After preprocessing, the final neural network operates on 52 processed features.

The raw dataset is not included in this public repository.

## Machine Learning Problem

The objective is to predict whether a customer will subscribe to a bank term deposit.

```text
0 = No subscription
1 = Subscription
```

## Final Neural Network Architecture

```text
Input: 52 processed features

Hidden Layer 1: 128 neurons
Hidden Layer 2: 64 neurons
Hidden Layer 3: 32 neurons

Dropout: 0.30

Output: Binary classification
```

Training configuration:

```text
Optimizer: Adam
Learning Rate: 0.0005
Batch Size: 64
```

## Hyperparameter Optimization

The project evaluated 108 neural network experiments.

The selected configuration was Experiment 19:

```text
Hidden layers: [128, 64, 32]
Learning rate: 0.0005
Dropout: 0.30
Batch size: 64
Optimizer: Adam
Best validation ROC-AUC: 0.93515
```

## Final Evaluation

| Metric | Result |
|---|---:|
| Validation ROC-AUC | 0.929965 |
| Average Precision | 0.611881 |
| Default threshold | 0.50 |
| Best F1 threshold | 0.75 |

The release preserves:

- Classification report
- Confusion matrix
- ROC curve
- Precision-Recall curve
- Test predictions
- Test probabilities
- Evaluation metrics

## Final Model

```text
models/final_optimized/final_optimized_ann_trained.keras
```

Authoritative SHA256:

```text
4b854d27a05386f3183989c1ebb2460e3cd0f0724e119d377cd8b1f87a23fb48
```

## Preprocessing Artifacts

```text
models/preprocessing_config.pkl
models/preprocessor.pkl
models/processed_feature_names.pkl
```

## Repository Structure

```text
README.md
LICENSE
requirements.txt
.gitignore
PACKAGE_MANIFEST.json

docs/final_release/
figures/final_evaluation/
models/
outputs/final_optimized_evaluation/
```

## Technologies

- Python
- NumPy
- pandas
- scikit-learn
- TensorFlow / Keras
- Matplotlib
- Google Colab / Jupyter

## Model Evaluation

The project emphasizes evaluation beyond accuracy.

The final release includes:

- ROC-AUC
- Average Precision
- Precision
- Recall
- F1-score
- Confusion matrix
- ROC curve
- Precision-Recall curve
- Threshold analysis

## Reproducibility

The repository preserves the final preprocessing artifacts, model artifact, evaluation outputs, metrics, and documentation required to understand and audit the final release.

The original raw dataset is intentionally not included.

## Release Integrity

Final model SHA256:

```text
4b854d27a05386f3183989c1ebb2460e3cd0f0724e119d377cd8b1f87a23fb48
```

Finalized GitHub release package SHA256:

```text
d5d97de98106a2198716804cb9aaa4290062e8bfe83497cb5d4295c909772947
```

## Project Status

**Completed — Final Release**

The model development, optimization, evaluation, validation, release packaging, and integrity verification phases have been completed.

## Author

**Getamesay Zegeye**

Machine Learning | Data Science | Neural Networks | MLOps
