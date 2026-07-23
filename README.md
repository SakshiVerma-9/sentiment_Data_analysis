# sentiment_Data_analysis
# 😊 Sentiment Analysis

A Machine Learning web application that predicts whether a given text or review expresses a **Positive** or **Negative** sentiment using Natural Language Processing (NLP) and a trained Machine Learning model.

---

## 🌐 Live Demo

👉 **Try the app here:**

https://sentimentdataanalysis-jckx6rge3ifntptul4xxkd.streamlit.app/



---

## ✨ Features

- Predicts Positive or Negative sentiment
- User-friendly Streamlit interface
- Text preprocessing using NLP
- TF-IDF Vectorizer for feature extraction
- Pre-trained Machine Learning model
- Fast and accurate predictions

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Joblib

---

## 📂 Project Structure

```
sentiment_Data_analysis/
│── app.py
│── sentiment_model.pkl
│── tfidf_vectorizer.pkl
│── sentimentData.csv
│── sentiment_Data.ipynb
│── NLP.ipynb
│── requirements.txt
│── README.md
```

---

## 📊 Dataset

The model is trained using the **sentimentData.csv** dataset, which contains labeled text data for sentiment classification.

---

## 🚀 How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/SakshiVerma-9/sentiment_Data_analysis.git
```

### 2️⃣ Go to the project folder

```bash
cd sentiment_Data_analysis
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## ☁️ Live Deployment

Deploy this project easily using **Streamlit Community Cloud**.

---

## 📸 Application Preview

Enter any sentence or review in the text box and click the **Predict** button.

Example:

```
Input:
This product is amazing. I really loved it!

Prediction:
Positive 😊
```

Example:

```
Input:
The service was very poor and disappointing.

Prediction:
Negative 😞
```

---

## 🔮 Future Improvements

- Add Neutral sentiment prediction
- Improve model accuracy
- Support multiple languages
- Display prediction confidence score
- Add sentiment visualization

---

## 👩‍💻 Author

**Sakshi Verma**

GitHub: https://github.com/SakshiVerma-9

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

---

## 📄 License

This project is intended for educational and learning purposes.
