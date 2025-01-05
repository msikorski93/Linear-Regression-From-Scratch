# Linear-Regression-From-Scratch
![ alt text ](https://img.shields.io/badge/license-MIT-green?style=&logo=)
![ alt text ](https://img.shields.io/badge/-Jupyter-F37626?logo=Jupyter&logoColor=white)
![ alt text ](https://img.shields.io/badge/-NumPy-013243?logo=Numpy&logoColor=white)
![ alt text ](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=TensorFlow&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Keras-D00000?logo=Keras&logoColor=white)

Linear and polynomial regression solutions made from scratch using TensorFlow 1 framework.

### New notebook for January 2025

Linear regression solutions built from scratch, without using fancy frameworks (only NumPy was implemented). We evaluated the performances with basic regression metrics as below:

|           Model           |    MSE   |    MAE   |    R²    |    RSS   |   Slope  | Intercept |
|:-------------------------:|:--------:|:--------:|:--------:|:--------:|:--------:|:---------:|
|      Gradient Descent     | 0.056114 | 0.208579 | 0.863454 | 6.733636 | 2.046441 | 11.358466 |
| Ordinary Least Squares #1 | 0.056114 | 0.20858  | 0.863454 | 6.733636 | 2.046379 | 11.358499 |
| Ordinary Least Squares #2 | 0.056114 | 0.20858  | 0.863454 | 6.733636 | 2.046379 | 11.358499 |
|        Scikit-Learn       | 0.056114 | 0.20858  | 0.863454 | 6.733636 | 2.046379 | 11.358499 |

We proved that our custom models are valid and accurate alternatives to the scikit-learn model, with virtually no noticeable difference in performance or output.
