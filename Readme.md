# 📰 Fake News Detector using Machine Learning

This is an AI-based Fake News Detection system that classifies whether a news article is **REAL** or **FAKE** using Natural Language Processing (NLP) and machine learning techniques. The model is trained on publicly available news data and is equipped with a clean UI using **Gradio**.

---

## 🚀 Features

<details>
<summary>📌 Click to expand features</summary>
- ✅ Cleans and preprocesses news data (removes stopwords, symbols, etc.)
- ✅ Uses **TF-IDF Vectorizer** to convert text into numerical features
- ✅ Trained on **Naive Bayes Classifier** for high accuracy
- ✅ Has a **Gradio-based Web UI** for real-time predictions
- ✅ Includes visualization with **confusion matrix**
</details>
---

## 📂 Dataset

- **Fake.csv** and **True.csv** from Kaggle
- Merged and labeled:
  - `0 = FAKE`
  - `1 = REAL`

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Gradio
- Matplotlib, Seaborn

---

## 🛠 How It Works

1. Load and clean the data  
2. Combine title + text and apply TF-IDF vectorization  
3. Split data into training and testing  
4. Train Naive Bayes model  
5. Evaluate with accuracy and confusion matrix  
6. Predict new news input using Gradio UI

---

## 🔍 Example Prediction

**Input:**  
> _"Breaking: President announces new economic reforms for stability."_

**Output:**  
> ✅ REAL News

---

## 🖼️ Screenshot

![Gradio UI]("UI .png")

---

## 💻 How to Run Locally

### 📦 Requirements

Install all dependencies:
```bash
pip install nltk scikit-learn gradio matplotlib seaborn pandas

---

## ▶️ Running the App
Use this command in your terminal:
```bash
python Fake_News_Detector.ipynb
Or launch the notebook using Jupyter/Colab and run all cells.

--- 

## 📜 License
This project is open-source under the MIT License.

---

```markdown
## 👨‍💻 Author

**Khubaib Jahanzaib Shah**
BSCS Student | AI & Software Developer

📫 [Email me](mailto:khubaibshah2002@gmail.com)
🌐 [GitHub Profile](https://github.com/khubbe)

---