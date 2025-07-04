# 🔍 Phishing URL Detection

Phishing URL Detection is a machine learning project that uses deep learning techniques (LSTM-based RNN) to identify and classify URLs as either *phishing* or *legitimate*. The goal is to improve online security by detecting malicious websites before a user accesses them.

---

## 📌 Project Objective

- Detect whether a given URL is *phishing* or *safe*
- Leverage deep learning (LSTM) to understand patterns in URLs
- Help users browse the web securely by flagging malicious links

---

## 🧠 Model Architecture

This project uses:
- *Recurrent Neural Network (RNN)* with *Long Short-Term Memory (LSTM)*
- *Embedding layer* to convert characters/tokens to vectors
- *Binary classification* (phishing vs. legitimate)

---

## 🛠 Tech Stack

Python TensorFlow Scikit-learn Pandas NumPy Matplotlib Jupyter

---

## 📂 Project Structure

Phishing-url-detection/ │ ├── dataset/ │   ├── phishtank.csv           # Dataset from PhishTank │   └── commoncrawl_legit.csv   # Legitimate URLs from Common Crawl │ ├── models/ │   └── phishing_model.h5       # Trained LSTM model │ ├── phishing_lstm.ipynb         # Jupyter Notebook (training & testing) ├── preprocess.py               # URL tokenization & preprocessing ├── utils.py                    # Helper functions ├── README.md                   # Project overview └── requirements.txt            # Dependencies

---

## 🧪 How It Works

1. URLs are tokenized and encoded as sequences.
2. Data is split into training and testing sets.
3. LSTM model is trained to learn malicious URL patterns.
4. Model outputs a binary classification (0 = Legit, 1 = Phishing).

---

## 📊 Dataset

- *Phishing URLs*: Collected from [PhishTank](https://www.phishtank.com/)
- *Legitimate URLs*: Sourced from [Common Crawl](https://commoncrawl.org/)
- Dataset is cleaned, balanced, and labeled accordingly.

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/Awasthi-22/Phishing-url-detection.git
cd Phishing-url-detection
pip install -r requirements.txt

Then, open the Jupyter Notebook:

jupyter notebook phishing_lstm.ipynb


---

✅ Results

Achieved ~96% accuracy on validation set

Effectively generalizes to unseen phishing URLs

Minimal false positives for legitimate domains



---

🧩 Future Enhancements

Integrate with browser extensions for real-time URL checks

Visualize model decision with attention layers

Deploy as a REST API or web application



---

🎓 Mini Project – B.Tech CSE (KTU)

> A deep learning-based approach for phishing URL detection using RNN (LSTM). Developed as part of the mini project for B.Tech CSE under the 2019 KTU scheme.




---

🤝 Credits

Dataset: PhishTank & Common Crawl

Frameworks: TensorFlow, Keras, Scikit-learn



---

### 📫 Contact

Feel free to connect:

- 📧 Email: aswathisajik1@gmail.com  
- 💼 LinkedIn: [linkedin.com/in/aswathiskumar2003](https://www.linkedin.com/in/aswathiskumar2003)
