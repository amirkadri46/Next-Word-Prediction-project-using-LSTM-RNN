# 🔮 Next Word Prediction using LSTM-RNN

This project is a deep learning-powered **Next Word Predictor** that uses an **LSTM (Long Short-Term Memory) Recurrent Neural Network** to suggest the most probable next word given an input sequence. Trained on Shakespeare’s *Hamlet*, the model is deployed with a clean **Streamlit** web interface.

---

## 🧠 Project Overview

The objective is to demonstrate sequence modeling using LSTM for next-word generation. It covers:
- Tokenization and sequence padding
- Training an LSTM model on a text corpus
- Predicting the next word based on input phrases
- Real-time interaction through a Streamlit web app

---

## 📂 Files and Structure

├── app.py # Streamlit web interface

├── experiemnts.ipynb # Jupyter Notebook for preprocessing and training

├── hamlet.txt # Text corpus used for training (Shakespeare's Hamlet)

├── next_word_lstm.h5 # Saved LSTM model (after training)

├── tokenizer.pickle # Fitted tokenizer object

├── requirements.txt # Python dependencies

└── README.md # Project documentation

## 🧪 Model Details
Type: LSTM (Recurrent Neural Network)

Training data: hamlet.txt

Framework: Keras (via TensorFlow)

Output: Next word with the highest predicted probability


## 💻 How It Works
User enters a partial phrase (e.g., "To be or not to").

The model tokenizes and pads the sequence.

Predicts the most likely next word using trained weights.

Displays the predicted word on the Streamlit UI.

PS: (This model is trained on limited data and got only 60% accuracy)

## 🔮 Future Enhancements
Predict the top 3 next word suggestions

Integrate pre-trained word embeddings (e.g., GloVe)

Add autocomplete sentence generator

Train on larger, modern text corpora
