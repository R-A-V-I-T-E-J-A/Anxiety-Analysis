# Anxiety-Analysis
This project focuses on developing an emotion classification model to detect human emotions from textual data. The model is built using a Bidirectional GRU (Gated Recurrent Unit) neural network and is trained to classify text into six emotions: Sadness, Joy, Love, Anger, Fear, and Surprise. The project includes preprocessing the dataset, building the model, and deploying it using a web interface for real-time emotion prediction.
# Features
* **Text Preprocessing:** Cleaned and processed over 416,000 text samples by removing URLs, special characters, stopwords, and numbers.
* **Neural Network Model:** A Bidirectional GRU model that captures both past and future context to improve emotion classification accuracy.
* **Real-Time Emotion Detection:** Deployed using Gradio, allowing users to input text and receive instant emotion predictions via a web interface.
* **Model Optimization:** Used techniques like batch normalization and dropout to prevent overfitting, achieving over 93% accuracy on the test set.
# Results
The model achieved an accuracy of 93.6% on the test dataset. Below are the key metrics and confusion matrix for model performance:

|Metric  |Value |
| ------------- | ------------- |
| Accuracy  | 93.6%  |
| Loss  | 0.097  |
| Precision  | 93.5%  |
| Recall  | 93.4%  |
