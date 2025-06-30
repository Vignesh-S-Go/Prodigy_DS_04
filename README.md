# Prodigy InfoTech Data Science Internship — Task 04

## 📄 Task Overview
**Task 04:**  
Analyze and visualize **sentiment patterns in social media data** to understand public opinion and attitudes towards specific topics or brands.

**Dataset Used:**  
[Twitter Entity Sentiment Analysis Dataset - Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

---

## 📊 Dataset Description
The dataset contains tweets labeled with their sentiments related to various brands, topics, or entities.

### Features include:
- **Tweet Text:** Content of the tweet.
- **Entity/Topic:** The subject (brand/topic) the tweet refers to.
- **Sentiment:** The sentiment label (`Positive`, `Negative`, or `Neutral`).

---

## 🛠️ Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- NLTK (Natural Language Toolkit)
- Scikit-learn

---

## 🔍 Steps Performed

### ✔️ Data Preprocessing
- Checked and handled missing values.
- Cleaned tweet texts:
  - Removed punctuation, numbers, links, and special characters.
  - Converted text to lowercase.
  - Removed stopwords using NLTK.

---

### ✔️ Sentiment Distribution Visualization
- Visualized the number of `Positive`, `Negative`, and `Neutral` tweets using count plots.

---

### ✔️ WordCloud Generation
Generated WordClouds for:
- **Positive Tweets:** Most common words in positive tweets.
- **Negative Tweets:** Frequent words associated with negative sentiments.
- **Neutral Tweets:** Common neutral expressions.

---

### ✔️ Sentiment Classification Model
- Used **TF-IDF Vectorizer** to convert text into numerical features.
- Built a simple **Naive Bayes Classifier** to predict sentiment.
- Split the dataset into **80% training** and **20% testing**.
- Evaluated the model using:
  - **Accuracy score**
  - **Classification report (Precision, Recall, F1-Score)**
  - **Confusion matrix visualization**

---

## 📈 Results

- The sentiment distribution was imbalanced with more neutral tweets.
- The Naive Bayes model performed with decent accuracy, showing effective text-based sentiment prediction capabilities.

---

## ✅ Conclusion
This task provided insights into the sentiment patterns of tweets related to various entities. By analyzing and visualizing this data, it's possible to understand public opinion, which can be useful for brands, marketers, and researchers.

---

## 🙏 Thank You
Thank you for reviewing my submission for **Task 04** of the **Prodigy InfoTech Data Science Internship**.

