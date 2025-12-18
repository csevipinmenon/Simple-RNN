

````markdown
# 🎬 Movie Review Sentiment Analysis using Simple RNN

## 📌 Project Overview
This project performs **sentiment analysis** on movie reviews using a **Simple Recurrent Neural Network (RNN)**.  
The model is trained on the **IMDB movie review dataset** provided by TensorFlow and classifies reviews as **positive** or **negative**.

---

## 🎯 Objective
- Learn how **RNNs** process sequential text data  
- Perform **binary sentiment classification**  
- Implement a basic NLP deep learning model using **TensorFlow & Keras**

---

## 📂 Dataset
- **Name:** IMDB Movie Reviews Dataset  
- **Source:** TensorFlow / Keras built-in dataset  
- **Size:** 50,000 movie reviews  
  - 25,000 training samples  
  - 25,000 testing samples  
- **Labels:**
  - `1` → Positive Review  
  - `0` → Negative Review  

---

## 🧠 Model Architecture
The model consists of the following layers:

1. **Embedding Layer** – Converts words into dense vector representations  
2. **SimpleRNN Layer** – Captures sequential dependencies in text  
3. **Dense Layer** – Sigmoid activation for binary classification  

---

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  


---

## ⚙️ Installation
Install the required dependencies using pip:

```bash
pip install tensorflow numpy 
````

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/csevipinmenon/Simple-RNN.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo-name
   ```

3. Run the script or notebook:

   ```bash
   streamlit run main.py
   ```

---

## 📊 Model Evaluation

* Evaluation metric: **Accuracy**
* Performance depends on:

  * Vocabulary size
  * Number of RNN units
  * Number of training epochs

---

## 📈 Results

* The model successfully classifies movie reviews into positive and negative sentiments
* Demonstrates the effectiveness of **Simple RNNs** for basic NLP tasks

---

## 🔮 Future Enhancements

* Use **LSTM** or **GRU** instead of Simple RNN
* Apply **pre-trained word embeddings** (GloVe, Word2Vec)
* Perform hyperparameter tuning for better accuracy



