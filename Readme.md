#Project Overview
This project aims to develop a deep learning model for predicting the next word in a given sequence of words. The model is built using Long Short Term Memory(LSTM) networks, which are well-suited for sequence prediction tasks. The project includes the following steps

1. Data Collection: We use the text of Shakespeare's "Hamlet" as our dataset. This rich,complex text provides a good challenge for our model.

2. Data Preprocessing: The data is tokenized,converted into sequence, and padded to ensure uniform input lengths. The sequences are the split into training and testing sets.

3. Model building: A LSTM model is constructed with an embedding layer, two LSTM layers and a dense output layer with a softmax activation function to predict the probability of next word.

4. Model Training: The model is trained using the prepared sequence , with early stopping implemented to prevent overfitting. Early stopping monitors the validation loss and stops training when the loss stops

5. Model Evaluation: The model is evaluated using a set of example sentences to test its ability to predict the next word accurately

6. Deployment: A streamlit web application to allow users to use it