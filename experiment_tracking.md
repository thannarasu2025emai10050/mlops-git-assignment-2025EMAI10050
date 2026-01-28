## Manual Experiment Tracking Table
| Experiment ID | Model Type | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|--------------------|---------------------|------------------------|----------------------------|-------------------------|----------------------|--------------|---------------|
| EXP-01 | Decision Tree | Default | None | All features | 80/20 |0.963 |0.983  |
| EXP-02 | Decision Tree | Max depth = 4 | Scaling | Selected | 80/20 |0.976 |0.995  |
| EXP-03 | KNN | k = 3  | Mean Imputation | All features | 80/20 |0.976 |1  |
| EXP-04 | KNN | k = 7  | Mean Imputation+Scaling | bill_length_mm,flipper_length_mm | 80/20 |0.976 |0.998  |
