
# NewsCheckmate

The NewsCheckmate Project is designed to identify and validate the authenticity of news articles. Leveraging the power of machine learning and natural language processing (NLP), this project analyzes text data to determine whether news content is genuine or fake. This solution aims to combat the spread of misinformation and enhance the reliability of news sources.

- ML Model: This fake news detection model is built using scikit-learn and incorporates advanced NLP techniques for precise text analysis.

## Model Mastery

- Impressive Accuracy: The model achieves an accuracy rate of 98%, making it highly effective in distinguishing between real and fake news.

## Technical Details

- Framework: scikit-learn

- NLP Techniques: Various natural language processing methods are employed for feature extraction and text analysis.

- Visualization: Matplotlib is used for data visualization and exploratory data analysis (EDA).

## Key Files

- Fake_News_Prediction.ipynb: This Jupyter Notebook contains the exploratory data analysis (EDA) of the dataset and the model training process. It includes data preprocessing, feature extraction, model training, and evaluation steps.

- svc_model.pkl: This file is the serialized model file containing the trained Support Vector Classifier (SVC) model. It can be used to load the model and make predictions.


## Usage

- Running the Notebook: Open and run the Fake_News_Prediction.ipynb notebook to perform exploratory data analysis and train the model. Ensure you have the necessary libraries installed and the dataset ready.

- Model Predictions: Load the svc_model.pkl file in your script or application to use the trained model for predicting news authenticity.

## Production
Explore the live implementation of the Project:
News Checkmate

This link: https://news-checkmate.netlify.app/ directs you to a web application where you can input news content to verify its authenticity. The application utilizes the trained model to predict whether the news is real or fake.

## Contributing
I welcome contributions to this project. Please submit a pull request for any improvements or new features. For major changes, consider opening an issue first to discuss the proposed modifications.
