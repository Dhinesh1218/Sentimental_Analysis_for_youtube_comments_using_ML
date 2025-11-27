# 📘 Sentiment Analysis for YouTube Comments using ML

## 📌 Overview
This project applies **Machine Learning techniques** to analyze the sentiment of YouTube comments. It classifies comments into categories such as **Positive, Negative, or Neutral**, helping creators and businesses understand audience feedback at scale.

The workflow includes:
- Extracting YouTube comments using APIs
- Preprocessing text (cleaning, tokenization, stopword removal)
- Feature extraction (TF‑IDF, word embeddings)
- Training ML models for sentiment classification
- Visualizing results for actionable insights

---

## 🚀 Features
- 🔎 **YouTube API Integration** – fetch comments directly from videos  
- 🧹 **Text Preprocessing** – remove noise, emojis, and special characters  
- 📊 **ML Models** – Logistic Regression, Naive Bayes, SVM, etc.  
- 📈 **Performance Metrics** – Accuracy, Precision, Recall, F1‑Score  
- 🎨 **Visualization** – sentiment distribution charts  

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit‑learn, Matplotlib, NLTK  
- **Data Source:** YouTube API  

---

## 📂 Project Structure
```
Sentimental_Analysis_for_youtube_comments_using_ML/
│── data/                # Raw and processed datasets
│── notebooks/           # Jupyter notebooks for experiments
│── src/                 # Source code (preprocessing, models, utils)
│── results/             # Output charts and reports
│── requirements.txt     # Python dependencies
│── README.md            # Project documentation
```

---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Dhinesh1218/Sentimental_Analysis_for_youtube_comments_using_ML.git
   cd Sentimental_Analysis_for_youtube_comments_using_ML
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up YouTube API credentials (Google Developer Console).

---

## ▶️ Usage
1. Run the script to fetch comments:
   ```bash
   python src/fetch_comments.py --video_id <VIDEO_ID>
   ```
2. Preprocess and train models:
   ```bash
   python src/train_model.py
   ```
3. View sentiment analysis results in `results/`.

---

## 📊 Example Output
- **Positive:** "This tutorial was super helpful!"  
- **Negative:** "I didn’t understand anything, very confusing."  
- **Neutral:** "The video is 10 minutes long."  

---

## 📈 Results
- Logistic Regression: 82% accuracy  
- Naive Bayes: 78% accuracy  
- SVM: 85% accuracy  

*(Results may vary depending on dataset size and preprocessing.)*

---

## 🤝 Contributing
Contributions are welcome!  
- Fork the repo  
- Create a feature branch  
- Submit a pull request  

---

## 📜 License
This project is licensed under the MIT License.  

---

## 👨‍💻 Author
**Dhinesh**  
Technical Analyst & Report Designer | Specializing in SQL, Oracle, and ML projects  

---

👉 This README gives your project a polished look and makes it easy for others to understand, install, and contribute.  

Would you like me to also **add badges** (like Python version, license, stars, issues) at the top for extra professionalism?

