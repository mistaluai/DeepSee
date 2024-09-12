### SD1.5 50 Batch Depth 15 Results
###### Inputs

| Class          | Quantity |
| -------------- | -------- |
| Real (0)       | 200      |
| Fake SD1.5 (1) | 200      |
With 50% Train, 50% Test and fixed random state 2003
###### Results
| Metric    | Residuals | De-noised Images |
| --------- | --------- | ---------------- |
| Accuracy  | 0.84      | 0.62             |
| F1        | 0.82      | 0.4              |
| Precision | 0.99      | 0.89             |
| Recall    | 0.7       | 0.25             |
*Confusion Matrix For Denoised Image*
![[ConfusionMAtrix-kNN-Denoised01.png]]

*Confusion Matrix For Residuals*![[ConfusionMAtrix-kNN-Residuals01.png]]

### SD1.5 100 Batch Depth 15 Results
###### Inputs

| Class          | Quantity |
| -------------- | -------- |
| Real (0)       | 400      |
| Fake SD1.5 (1) | 400      |
With 50% Train, 50% Test and fixed random state 2003
###### Results
| Metric    | Residuals | De-noised Images |
| --------- | --------- | ---------------- |
| Accuracy  | 0.86      | 0.51             |
| F1        | 0.84      | 0.04             |
| Precision | 0.99      | 0.80             |
| Recall    | 0.72      | 0.02             |
*Confusion Matrix For Denoised Image![[ConfusionMAtrix-kNN-Denoised02.png]]*
*Confusion Matrix For Residuals*
![[ConfusionMAtrix-kNN-Residuals02.png]]