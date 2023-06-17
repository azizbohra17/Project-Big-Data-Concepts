# Wine Quality Prediction

This project aims to develop a wine quality prediction model using machine learning techniques. The dataset used for this project is the Wine Quality Dataset, obtained from Kaggle and developed by M YASSER H. The dataset contains physicochemical attributes and sensory attributes of wines, which will be used to predict the quality of the wine.

## Dataset

The Wine Quality Dataset can be found on Kaggle at the following link:
[https://www.kaggle.com/datasets/yasserh/wine-quality-dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)

## Project Steps

The project follows a systematic methodology and involves the following steps:

1. **Data Gathering**: Relevant data related to wine quality is collected, including physicochemical attributes such as pH, acidity, and alcohol content, as well as sensory attributes such as taste and aroma.

2. **Data Preprocessing**: The collected data is preprocessed to handle outliers, imbalance in the target variable, and other cleaning tasks. Exploratory data analysis is also performed to visualize the data and identify patterns.

3. **Model Development**: Machine learning pipelines are used for data processing and feature engineering. The data is then fed into a prediction model to train and evaluate its performance.

4. **Concurrency and Scalability**: Apache Spark, a fast and distributed data processing framework, is utilized to process multiple requests concurrently. This allows for efficient handling of large volumes of data and real-time predictions.

5. **Deployment**: Once the application is ready and tested, a server is set up using JetStream2, a virtualization platform. The server enables users to access the application and pass data for predictions.

## Requirements

The following software and libraries are required to run the code:

- Python (version 3.8.8)
- Apache Spark (version 3.4.0)
- JDK (version 11.0.18)

## Usage

To use the wine quality prediction application, follow the steps below:

1. Clone this repository to your local machine.
2. Run the application using the provided scripts or execute the main entry point file.
3. Access the application through the provided server URL and pass the required data for predictions.

Please refer to the documentation and source code for more detailed instructions on running and using the application.

## Contributors

- [Aziz Bohra](https://github.com/azizbohra17)


