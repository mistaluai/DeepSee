
##### Inputs

| Class          | Quantity |
| -------------- | -------- |
| Real (0)       | 200      |
| Fake SD1.5 (1) | 200      |
With 50% Train, 50% Test and fixed random state 2003
##### Results

###### Magnitude Denoised Image Results
| Metric    | Value |
|-----------|-------|
| Accuracy  | 0.67  |
| Precision | 0.74  |
| Recall    | 0.51  |
| F1 Score  | 0.61  |
![[kNN-SD1.5-mag_denoised.png]]
###### Phase Denoised Image Results
| Metric    | Value |
|-----------|-------|
| Accuracy  | 0.57  |
| Precision | 0.73  |
| Recall    | 0.20  |
| F1 Score  | 0.32  |
![[kNN-SD1.5-phase_denoised.png]]
###### Magnitude Residual Image Results
| Metric    | Value |
|-----------|-------|
| Accuracy  | 0.83  |
| Precision | 0.87  |
| Recall    | 0.76  |
| F1 Score  | 0.81  |
![[kNN-SD1.5-mag_residuals.png]]
###### Phase Residual Image Results
| Metric    | Value |
|-----------|-------|
| Accuracy  | 0.56  |
| Precision | 0.63  |
| Recall    | 0.24  |
| F1 Score  | 0.35  |
![[kNN-SD1.5-phase_residuals.png]]