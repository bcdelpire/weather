# Demo

Weather forecasts are used constantly in our daily lives. They are important in industry, agriculture, safety, and more. Research on using deep learning techniques for weather forecasting has been performed for over a decade, with most involving the study of Recurrent Neural Networks (RNNs), Long Short Term Memory Networks (LSTM), and Convolution Neural Networks (CNNs) for making weather predictions. Typically, uncertainty measurements on these predictions are not included in the metrics of these studies. In this research we aim to compare an LSTM model, a CNN model, and a combined CNN-LSTM model in making single-shot, 24-hour temperature predictions using a variety of weather features as input. In comparing the performances of these models, we find that the LSTM model has the lowest mean absolute error of the three while the CNN model has the least uncertainty in its predictions.

In this demo, you can run the Monte Carlo predictions on the test data and compare the three model's forecasts for any day in the testing data.

# Steps

1. Download the Jupyter Notebook and the three models.
    - Deployment.ipynb
    - lstm32model
    - cnn_model.h5
    - combined_model.h5
    
2. Upload the files to a Jupyter Notebook environment of your choice.
    - https://jupyterhub.cs.mtsu.edu/azuread/hub/home

3. Open the notebook, Deployment.ipynb, and run!

# Resources

https://www.tensorflow.org/tutorials/structured_data/time_series#single-shot_models
https://towardsdatascience.com/single-and-multi-step-temperature-time-series-forecasting-for-vilnius-using-lstm-deep-learning-b9719a0009de
https://raw.githubusercontent.com/Eligijus112/Vilnius-weather-LSTM/main/data/weather.csv
