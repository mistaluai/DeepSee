###### Inputs

| Class          | Quantity |
| -------------- | -------- |
| Real (0)       | 200      |
| Fake SD1.5 (1) | 200      |
With 50% Train, 50% Test and fixed random state 2003
###### Network Depth
| Depth | Results              |
| ----- | -------------------- |
| 5     | [[#Depth 5 Results]] |
| 25    |                      |
| 40    |                      |

## Results
#### Depth 5 Results
###### Spatial Domain

| Metric    | Denoised Image | Residual Image |
|-----------|----------------|----------------|
| Accuracy  | 0.66           | 0.81           |
| Precision | 0.93           | 0.99           |
| Recall    | 0.32           | 0.63           |
| F1 Score  | 0.48           | 0.77           |
![[depth-5-denoised.png]]
![[depth-5-residuals.png]]
###### Frequency Domain

| Metric    | Magnitude Denoised | Phase Denoised | Magnitude Residual | Phase Residual |
| --------- | ------------------ | -------------- | ------------------ | -------------- |
| Accuracy  | 0.81               | 0.67           | 0.87               | 0.50           |
| Precision | 0.80               | 0.62           | 0.88               | 0.36           |
| Recall    | 0.81               | 0.84           | 0.85               | 0.02           |
| F1 Score  | 0.80               | 0.71           | 0.86               | 0.04           |
![[depth-5-mag_denoised.png]]
![[depth-5-phase_denoised.png]]

![[depth-5-mag-residual.png]]

![[depth-5-phase-residual.png]]


#### Depth 25 Results
###### Spatial Domain
| Metric    | Denoised Image | Residual Image |
| --------- | -------------- | -------------- |
| Accuracy  | 0.52           | 0.85           |
| Precision | 0.88           | 0.97           |
| Recall    | 0.04           | 0.72           |
| F1 Score  | 0.07           | 0.83           |
![[depth-25-denoised.png]]![[depth-25-residual.png]]
###### Frequency Domain

| Metric    | Magnitude Denoised | Phase Denoised | Magnitude Residual | Phase Residual |
|-----------|--------------------|----------------|--------------------|----------------|
| Accuracy  | 0.76               | 0.56           | 0.83               | 0.49           |
| Precision | 0.79               | 0.56           | 0.82               | 0.43           |
| Recall    | 0.71               | 0.48           | 0.84               | 0.10           |
| F1 Score  | 0.74               | 0.52           | 0.83               | 0.16           |
![[depth-25-mag_denoised.png]]![[depth-25-phase_denoised.png]]![[depth-25-mag-residual.png]]![[depth-25-phase_residual.png]]