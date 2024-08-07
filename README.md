# Next Word Prediction using Bidirectional LSTM (BI-LSTM) on Medium Articles Dataset

## Description
This project demonstrates the use of a Bidirectional Long Short-Term Memory (BI-LSTM) network for predicting the next word in a sequence of words using a dataset of Medium articles. The BI-LSTM model is designed to capture contextual information from both the past and future within the text, providing improved predictions for the next word compared to traditional unidirectional models.

## Key Features
- **Bidirectional LSTM Network**: Integrates both forward and backward sequences to enhance contextual understanding.
- **Next Word Prediction**: Generates predictions for the next word based on the input sequence from Medium articles.
- **Model Training and Evaluation**: Includes code for training the BI-LSTM model and assessing its performance.
- **Visualization**: Displays plots for training accuracy and loss to track model performance.
- **Preprocessing**: Contains steps for preparing the Medium articles dataset, including tokenization and padding.
- **Prediction Functionality**: Provides functionality to predict the next word given a partial sequence from an article title or content.

## Objective
The primary objective of this project is to develop and train a BI-LSTM model to predict the next word in a sequence of text extracted from Medium articles. By employing bidirectional LSTM layers, the model aims to achieve higher accuracy in predicting the next word by considering both preceding and succeeding words in the sequence.

## Insight
- **Enhanced Contextual Understanding**: The bidirectional nature of the LSTM enables the model to understand context from both directions, leading to more accurate word predictions.
- **Dataset Specificity**: Training on Medium articles allows the model to be tuned for the language and style specific to Medium's content.
- **Training Insights**: Visualization of accuracy and loss provides valuable insights into the model's learning process and helps in fine-tuning.
