 Your results table: MAE for the mean baseline, MAE for the median baseline, and MAE for your linear regression model, all measured on the test set.

| Model             | MAE           |
| ----------------- | ------------: |
| Mean baseline     |         10.32 |
| Median baseline   |         10.33 |
| Linear Regression |          1.92 |







 Two sentences answering Task T2: did the 70/30 split with seed 7 change your conclusion, and what does that tell you about how much to trust a single split?

The MAE increased to 2.10 in the 70/30 split compared to 19.2 in the first one, tho it doesnt change conclusion, as both are performing well, a single train-test split should not be treated as the only evidence of model performance.