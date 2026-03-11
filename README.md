## Arsitektur Part 1

1. **Kaggle Climate Dataset**
2. **Data Merge Pipeline**
3. **Data Cleaning**
4. **Feature Engineering**
5. **Model Training**
   - Logistic Regression (LR)
   - Random Forest (RF)
   - XGBoost
6. **Bayesian Model Averaging**
7. **Model Evaluation**
8. **Model Registry (.pkl)**


## Arsitektur Part 2

```mermaid
flowchart TD
    A[Indonesia Climate Dataset] --> B[Data Preprocessing]
    B --> C[AI Models]
    C --> D[LSTM Forecast]
    C --> E[XGBoost Spatial]
    D --> F[Prediction Engine]
    E --> F