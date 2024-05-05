# Sentiment Analysis of Twitter Dataset
In this project, we delve into understanding the sentiment expressed in tweets through the lens of machine learning. Our goal is to effectively classify tweets into positive, negative, or neutral sentiments utilizing a combination of Random Forest classification and TF-IDF (Term Frequency-Inverse Document Frequency) vectorization techniques. 

## Project Overview

- **Data Preprocessing**: We perform thorough data cleaning and preprocessing on the Twitter dataset to ensure quality and consistency in our analysis.
  
- **Feature Extraction**: Using TF-IDF vectorization, we extract relevant features from the text data, transforming it into numerical representations suitable for machine learning algorithms.
  
- **Model Training**: Leveraging Random Forest classification, we train a robust model capable of accurately predicting sentiment labels for tweets.

- **Model Evaluation**: We assess the performance of our trained model using appropriate evaluation metrics to ensure its effectiveness in sentiment classification.

## Important Note

Please ensure to perform all the necessary steps of data cleaning, preprocessing, and model building within a Jupyter Notebook or Google Colab environment. This includes tasks such as text preprocessing, feature extraction, model training, and evaluation. Once the model is trained and evaluated satisfactorily, save it as a pickle file (*.pkl) using Python's pickle module or joblib library. This pickle model file will be utilized in the app.py file for sentiment analysis. By following this approach, we maintain consistency and reproducibility, ensuring that the model used in the application accurately reflects the one developed during the analysis phase.

## Repository Contents

In this repository, you'll find:

- Jupyter Notebook: Contains the code for data preprocessing, feature extraction, model training, and evaluation.
- Datasets: The Twitter dataset used for sentiment analysis.
- README: Provides an overview of the project and instructions for running the code.
- app.py: Python file for deploying the trained model into a Streamlit web application.

## Instructions

To run the movie recommendation system:

1. Clone this repository to your local machine.
   
2. Run the Streamlit app using the following command:
   streamlit run app.py
   
3. Input your text and click on the "Predict" button to get the prediction.

