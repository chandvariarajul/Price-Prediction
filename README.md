# Price-Prediction
Bitcoin Price Prediction


Project Findings
The project aims to predict Bitcoin prices using historical data and a Support Vector Regression (SVR) model. The dataset includes daily Bitcoin prices, and the model is trained to predict future prices based on this data.

Quantified Findings
Data Overview:

The dataset contains Bitcoin prices from August to September 2024.
Sample prices from the dataset:
2024-09-08: $54,476.60
2024-09-07: $54,156.50
2024-09-06: $53,966.80
Model Used:

Support Vector Regression (SVR) Model: Implemented using a Radial Basis Function (RBF) kernel with parameters 
- 𝐶 = 1000.0 C=1000.0 and 
- 𝛾 = 0.00001 γ=0.00001.

Data Processing:

The dataset was split into training and testing sets with an 80-20 split.

A 30-day prediction window was set to predict future prices.

Prediction Results:

- SVR Model Accuracy: The model achieved an accuracy of 11.88%.
- Predicted Prices vs. Actual Prices for the test set:
- Predicted: $64,290.40, Actual: $66,773.10
- Predicted: $62,069.03, Actual: $56,057.80
- Predicted: $61,813.46, Actual: $61,699.70

Predicted Prices for Next 30 Days:

- Day 1 Prediction: $62,187.50
- Day 15 Prediction: $63,870.71
- Day 30 Prediction: $62,870.24

Price Range for Predictions:
- Predicted prices for the next 30 days range from $61,277.77 to $65,638.90.

Summary Insights
- The model's prediction accuracy is relatively low (11.88%), suggesting the need for further optimization, possibly by adjusting model parameters or incorporating additional features.
Predicted prices show a trend of slight fluctuation within a range of $4,361.13 over the next 30 days.
The SVR model's predictions are somewhat consistent but require improvements for more reliable forecasting of Bitcoin prices.

Contributing

Contributions are welcome! Please feel free to submit a pull request or raise an issue for any bugs or suggestions for improvements.
License This project is licensed under the MIT License - see the LICENSE file for details.

Contact For any questions or feedback, please contact rajul.work@outlook.com.
