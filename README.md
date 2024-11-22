# **Sentiment Analysis Using Sequential Models**

A powerful sentiment analysis model built using Multiple Sequential Models like (LSTM, GRU, Bidirectional LSTM) to classify text as positive or negative. This project demonstrates practical usage of embedding layers and sequential modeling.

# **Features**

- Text Preprocessing: Tokenization, padding, and custom word index creation.
- Embedding Layer: Converts words into dense vector representations.
- Recurrent Neural Network: Captures the sequential nature of text data using LSTM/GRU layers.
- Binary Classification: Predicts positive or negative sentiment of a given text input.

# **Technologies Used**

- Python: Core programming language.
- TensorFlow/Keras: Deep learning framework for model building.
- NumPy & Pandas: Data manipulation and processing.
- Tensorboard: For Deep Learning Visualization.

# **Installation**

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sentiment-analysis-rnn.git

2. Install the required packages:
   ```bash
   pip install -r requirements.txt

3. Run the project:
   ```bash
   python app.py

# **Dataset**

- The model is trained on the IMDB dataset (On Kaggle).
- To replace with a custom dataset, upload your .csv file and adjust the preprocessing script accordingly.

# **How to Use the Project**

1. Input Text: Provide a text string to the model for prediction.
2. Output: The model will classify the text as either Positive or Negative or Neutral.

Example:
    ```bash
    Input: "The movie was excellent and very engaging."
    Output: Positive Sentiment (Confidence: 98%)

# **Functionalities**

- Custom Word Index: Handles unknown words gracefully using a default index.
- Padding and Truncation: Ensures consistent input shape for the Embedding Layer.
- Saved Model: Export and load trained models for inference.

## **About Me**  

Hi! I'm [Talha](https://github.com/anonymous298), a passionate developer and tech enthusiast focused on building impactful projects. I specialize in **AI/ML**, and crafting efficient solutions for complex problems.  

### **Skills**  
- 🧠 Artificial Intelligence & Machine Learning  
- 💻 Web Development (Frontend & Backend)  
- 📊 Data Analysis & Visualization  

### **Connect with Me**  
- [GitHub](https://github.com/anonymous298)  
- [LinkedIn](https://linkedin.com/in/muhmmad-talha937/)  
