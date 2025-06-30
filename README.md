# 📊 ChatGPT Review Analysis

## 🧠 Overview  
This project analyzes **196,727 user reviews** of **ChatGPT**, OpenAI’s AI chatbot, to uncover:
- Overall sentiment trends  
- Frequently praised features  
- Common user complaints  

Using **Python in Google Colab**, this analysis generates **actionable insights** to enhance user satisfaction. It combines **sentiment analysis**, **keyword extraction**, and **visualizations** to provide a complete review of user feedback.

---

## ❓ Problem Statement & Objectives

- **Problem**: Understand user sentiment and feedback to identify ChatGPT’s strengths and areas for improvement.
- **Relevance**: As a widely used tool for education, productivity, and research, user feedback is vital for OpenAI's strategic growth.
- **Business Question**:  
  _“What do users love about ChatGPT, and what issues do they face?”_
- **Hypothesis**:  
  Users will praise its helpfulness, but raise concerns about stability, pricing, and accessibility.
- **Goal**:  
  Analyze reviews to provide **data-driven recommendations** for product improvement.

---

## 🗂 Dataset

- **File**: `chatgpt_reviews.csv`  
- **Source**: Anonymized app store reviews  
- **Size**: 196,727 rows  
- **Fields**:
  - `review_id`  
  - `review`  
  - `rating`  
  - `review_date`  

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/VishnuKanna26/ChatGPT-Review-Analysis.git
cd ChatGPT-Review-Analysis
````

Install required Python packages:

```bash
pip install pandas textblob nltk wordcloud matplotlib seaborn
```

Download NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## 🚀 How to Run in Google Colab

1. Open the Colab notebook:
   `notebooks/ChatGPT_Review_Analysis.ipynb`

2. Upload the dataset:

   * Use `chatgpt_reviews.csv`
   * Upload to `/content` inside Colab

3. Run all cells, following these steps:

   * ✅ Step 1: Data Preparation (cleaning, formatting)
   * ✅ Step 2: Sentiment Analysis (TextBlob polarity, subjectivity)
   * ✅ Step 3: Keyword Extraction (using NLTK)
   * ✅ Step 4: Visualization (seaborn plots, word clouds)
   * ✅ Step 5: Summary of Insights

---

## 📂 Output Files

You can find the generated insights and visuals in the Colab **Files** tab:

* `outputs/summary_findings.txt`
* `outputs/sentiment_distribution.png`
* `outputs/sentiment_vs_rating.png`
* `outputs/wordcloud_positive_reviews.png`

---

## 🧪 Methodology

* **Data Cleaning**: Removed nulls, standardized text, converted data types
* **Exploratory Data Analysis**:
  Used bar plots, histograms to visualize sentiment and rating distributions
* **Sentiment Analysis**:
  Used `TextBlob` to classify polarity and subjectivity
* **Text Analysis**:
  Used `nltk` to tokenize, remove stopwords, and extract keywords
* **Visualization**:
  Used `seaborn`, `matplotlib`, and `wordcloud` for meaningful graphics

---

## 📈 Results & Insights

| Metric        | Value         |
| ------------- | ------------- |
| 📊 Positive   | 76.3%         |
| 😐 Neutral    | 19.5%         |
| 😡 Negative   | 4.1%          |
| ⭐ Mean Rating | 4.50 out of 5 |

### 💬 Praised Features

* *"Helpful"*, *"useful"*, *"great"*, *"easy"*
  (identified through keyword frequency and word clouds)

### ⚠️ User Complaints

* App instability → *"App not working"*
* Subscription issues → *"Can't access paid features"*
* Accessibility → *"Text verification failed"*

---

## ✅ Recommendations

* Improve server stability and reliability
* Reevaluate subscription/payment models
* Add fallback for SMS/text verification (e.g., email verification)

---

## 🎥 Project Demo

Watch the full recorded walkthrough:
📹 **[Watch on YouTube](https://your-link.com)**
🕒 Duration: \~15 minutes
📋 Covers: Problem framing, data prep, analysis steps, visualizations, and findings

---

## 📁 Code & Repository Structure

```
ChatGPT-Review-Analysis/
├── data/
│   └── chatgpt_reviews_sample.csv
├── notebooks/
│   └── ChatGPT_Review_Analysis.ipynb
├── outputs/
│   ├── summary_findings.txt
│   ├── sentiment_distribution.png
│   └── wordcloud_positive_reviews.png
├── README.md
```

* Code is well-commented and organized into clear, logical steps.
* Git is used for version tracking.
* Notebook runs end-to-end without errors.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
Feel free to use, modify, or share it with attribution.

---

---

## 🤝 Contributing

Want to improve or extend the project (e.g., support for multilingual analysis)?
You're welcome to:

* Fork the repo
* Submit pull requests
* Report issues

---

## 📬 Contact

For feedback, collaboration, or questions, reach out:

* ✉️ Email: \[[vishnukanna268@gmail.com](mailto:vishnukanna268@gmail.com)]
* 🐙 GitHub: \[[My-github-profile](https://github.com/VishnuKanna26)]

