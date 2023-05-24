# Real-Estate-Price-Prediction-using-ANN
The House Price Prediction Model is a machine learning model developed using scikit-learn and TensorFlow libraries. The objective of this project was to build a model capable of predicting house prices based on various features.

The project began with importing the necessary libraries, including scikit-learn for data preprocessing and model evaluation, and TensorFlow for building and training the neural network model. The trained model was saved for future use.

To assess the model's performance, three key evaluation metrics were utilized: mean absolute error (MAE), root mean squared error (RMSE), and explained variance score. The MAE measures the average absolute difference between the predicted and actual house prices. In this model, the MAE was calculated to be approximately $108,063.24, indicating the average prediction error.

The RMSE, calculated by taking the square root of the mean squared error, provides a measure of the spread of prediction errors. For this house price model, the RMSE was approximately $175,085.79, indicating a wider spread of errors compared to the MAE.

The explained variance score measures the proportion of variance in the target variable (house prices) that is explained by the model. The score obtained for this model was approximately 0.802, indicating that around 80.2% of the variance in house prices is accounted for by the model's predictions.

Additionally, the mean house price in the dataset was calculated to be approximately $540,296.57, providing a reference point for understanding the model's performance in relation to the average price.

Visualizations were utilized to enhance the understanding of the model's predictions and errors. A scatter plot was created to compare the predicted house prices against the actual prices. The plot included a red line representing a perfect prediction, allowing for visual assessment of how closely the predictions aligned with the actual values.

To analyze the prediction errors, a histogram was generated to visualize the distribution of errors. By calculating the difference between the actual house prices and the predicted prices, the histogram provided insights into the magnitude and frequency of errors, highlighting any patterns or biases present in the model's predictions.

Lastly, the model's prediction capability was demonstrated on a single house instance. The features of a specific house were selected, preprocessed, and scaled using a feature scaling technique. The model was then applied to this instance, resulting in a predicted price of approximately $234,161.56.

In conclusion, the House Price Prediction Model is a machine learning model developed using scikit-learn and TensorFlow. It demonstrates the ability to predict house prices based on various features. The model's performance was evaluated using metrics such as MAE, RMSE, and explained variance score, and visualized through scatter plots and histograms. This model provides valuable insights into predicting house prices and can be used to inform real estate decisions.
