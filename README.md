# Machine Learning Clustering and Regression Project


## Kaggle Profile

You can find more of my projects and notebooks on my [Kaggle profile](https://www.kaggle.com/code/furkancinko/aygaz-bootcamp).


## Overview

This project explores unsupervised learning for clustering using K-Means and supervised learning using Support Vector Regression (SVR). The dataset was processed and analyzed to determine optimal clustering parameters and regression model performance. The key goal was to identify patterns in the data using K-Means clustering and to build a robust SVR model for prediction.


## Key Highlights
- **Final Silhouette Score**: `0.0634` (indicating moderate clustering separation).
- **Optimal K for K-Means Clustering**: `25` clusters.
- **Best SVR Model**:
  - **MSE**: `59.01`
  - **R² Score**: `0.58`
  - **Best Parameters**: `{'regressor__C': 1, 'regressor__epsilon': 0.1, 'regressor__gamma': 'auto'}`


## Project Components

1. **Clustering using K-Means**:
    - The clustering process aimed to partition the data into distinct clusters to identify patterns.
    - The optimal number of clusters was found to be `25` based on the Silhouette Score.
    - **Final Silhouette Score**: `0.0634`, suggesting moderately well-separated clusters.

2. **Regression using SVR**:
    - Support Vector Regression (SVR) was used to build a predictive model for regression analysis.
    - After hyperparameter tuning, the best SVR model achieved:
        - **MSE**: `59.01`
        - **R² Score**: `0.58`
    - These scores indicate moderate predictive power, suggesting that the model is a reasonable fit for the data.

3. **Model Hyperparameters**:
    - The following hyperparameters were identified as optimal for the SVR model:
      ```
      {'regressor__C': 1, 'regressor__epsilon': 0.1, 'regressor__gamma': 'auto'}
      ```
      

## Conclusion

This project demonstrates the application of K-Means clustering and Support Vector Regression (SVR) for analyzing and modeling data. While the results are promising, there is potential for further optimization and exploration of alternative methods to improve both clustering and regression performance.
