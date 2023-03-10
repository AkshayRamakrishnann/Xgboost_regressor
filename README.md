# Crop Recommendation using Intel One API XGBoost Regressor

![dataset-cover](https://user-images.githubusercontent.com/111365771/224358048-d6e5f81d-0ebc-421c-824f-fe6d1c12478d.jpg)

## Introduction

This project uses the Intel One API XGBoost regressor to predict crop yield based on environmental factors. The dataset used for this project is obtained from Kaggle, and includes data on the soil type, temperature, humidity, rainfall, pH value, and other environmental factors for various regions in India.
XGBoost is an open-source machine learning library that is widely used for building tree-based models, particularly gradient boosting models. It is known for its speed and accuracy, and has won numerous Kaggle competitions.
Intel One API is a unified programming model that simplifies the development of high-performance applications across diverse architectures, including CPUs, GPUs, and FPGAs. It allows developers to write code that can automatically take advantage of the hardware features available on a particular platform, without requiring them to write separate code paths for each architecture.

## OneAPI
In this project, we use the Intel One API implementation of XGBoost to train a regression model that can predict crop yield based on environmental factors. We leverage the performance and scalability features provided by OneAPI to train the model on multiple cores or a GPU, depending on the hardware resources available.

## Models Used
We use the XGBoost regressor for this project, which is a gradient boosting algorithm that uses decision trees as base models. XGBoost is known for its speed and accuracy, and has been widely used in industry and academia.

## Methods and Materials
We preprocess the crop recommendation dataset by converting categorical variables into one-hot encodings, and splitting the data into training and testing sets. We then train the XGBoost regressor on the training data using the OneAPI implementation, and evaluate its performance on the testing data using the mean squared error (MSE) and R-squared metrics.

## Results
The mean squared error (MSE) of the XGBoost regressor on the test data is 29.96, and the R-squared value is 0.25.

Note that accuracy is not presented for regression models. This is because accuracy is a metric that measures the proportion of correct predictions in a classification problem. In regression problems, we are trying to predict a continuous variable, so accuracy is not a meaningful metric. Instead, we use metrics such as mean squared error (MSE) or R-squared to evaluate the performance of regression models.

The MSE of 29.96 indicates that the model has a relatively high amount of error in its predictions, while the R-squared of 0.25 indicates that only 25% of the variability in the target variable is explained by the model.

## Conclusion
In conclusion, the Intel One API XGBoost regressor can be used to predict crop yields based on environmental factors. By leveraging the performance and scalability features provided by OneAPI, we can train the model on multiple cores or a GPU, depending on the hardware resources available. XGBoost is a powerful and popular algorithm for building tree-based models, and is suitable for a wide range of regression and classification problems.



