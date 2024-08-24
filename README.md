# Results and Discussion

# Model Performance

# Random Forest Regressor:

# Evaluation Metrics:
# Mean Absolute Error (MAE): 1396.397
# Root Mean Squared Error (RMSE): 2232.042
# R-squared (R²): 0.722
# Discussion:

# The Random Forest Regressor demonstrated strong performance, achieving a Mean Absolute Error (MAE) of 1396.397, 
# which indicates that the model's predictions deviated by an average of R1396.40c from the actual flight prices. 
# The Root Mean Squared Error (RMSE) of 2232.042 suggests that the model's predictions are relatively precise across 
# the range of flight prices. The R² value of 0.722 shows that the model accounts for approximately 72.2% of 
# the variance in flight prices, indicating a good model fit, especially given the inherent complexity of the 
# prediction task.

# Hyperparameter Tuning Results:

# Upon optimizing the Random Forest model using RandomizedSearchCV, the best hyperparameters identified were:

# n_estimators: 1100
# min_samples_split: 10
# min_samples_leaf: 2
# max_features: sqrt
# max_depth: 15
# Discussion:

# The hyperparameter tuning process enhanced the model's performance by fine-tuning these parameters, resulting in more accurate predictions. This tuning was particularly effective in capturing the non-linear relationships within the data, thereby improving the model's overall predictive capability.

# Key Insights

# Feature Importance:

# The analysis identified Total_Stops, Duration, and Airline as the most significant features influencing flight prices. The results suggest that flights with longer durations and more stops tend to have higher prices, which is consistent with industry patterns.

# Visualizations:

# Scatter Plot of Flight Duration vs. Price: Demonstrated a clear positive correlation, where longer flight durations were associated with higher ticket prices.
# Count Plot of Total Stops: Revealed that non-stop flights were the most frequent, but as the number of stops increased, so did the variability in ticket prices.
# Conclusion and Recommendations

# Conclusion:

# The predictive model developed in this project effectively forecasted flight prices with a high degree of accuracy, as reflected by an R² of 0.718. The Random Forest Regressor, especially after hyperparameter optimization, emerged as the most effective model, successfully capturing the complex interactions between features such as Total_Stops, Duration, and Airline.

# Key Findings

# Model Performance: The tuned Random Forest model provided reliable predictions, making it a valuable tool for understanding and forecasting air ticket pricing trends.
# Feature Importance: The analysis underscored the critical role of factors like Total_Stops and Duration in determining flight prices, offering essential insights for both airlines and consumers.
# Recommendations

# For Airlines:

# Dynamic Pricing Strategies: Airlines should implement models like the Random Forest Regressor to optimize real-time pricing strategies, ensuring competitive yet profitable ticket prices.
# For Consumers:

# Informed Booking: Consumers can leverage insights from such models to identify the best times to purchase tickets, potentially saving money by avoiding peak pricing periods.
# By applying these predictive insights, stakeholders can make data-driven decisions that enhance profitability and customer satisfaction in the competitive aviation market.
