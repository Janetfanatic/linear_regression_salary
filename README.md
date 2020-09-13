# Evaluation the performance of models and with recommendation on whether they should be used to predict credit risk.

## Oversampling

### Naive Random Oversampling
#### Precision in finding likely low risk is high and finding likely high risk is low. Sensitivity in finging true high risk and low risk are similar, with values nearly 70%. F1 score is low for high risk and high for low risk with pronounced imbalance. Balance accuracy score may seem high but it is lower than what is suggested.

### SMOTE Oversampling
#### Precision in finding likely low risk is high and finding likely high risk is low. Sensitivity in finding true high and low risk similar, with values less than 65%. F1 score is low for high risk and high for low risk with pronounced imbalance. Balance accuracy score may seem high but is is lower than what is suggested.

### Undersampling
####  Precision in finding likely low risk is high and finding likely high risk is low. Sensitivity in finding true high 61% and low risk 57% . F1 score is low for high risk and high for low risk wit hpronounced imbalance.  Balance accuracy score may seem high but it is lower than what is suggested.

### Combination (Over and Under) Sampling
#### Precision in finding likely low risk is high and finding likely high risk is low. Sensitivity in finding true high risk is high at 70% and low risk at 57% . F1 score low for high risk and high for low risk, with pronounced imbalance. Balance accuracy score may seem high but it is lower than what is suggested.

### Based on my interpretation of the results, I would recommend use of Combination (Over and Under) Sampling.  I have chossen this analysis due to its high precision in identifying low risk and Moderate Seneitivity in finding High risk.
