# Sentiment-Showdown-Logistic-vs-SVM-vs-RF
 Sentiment analysis on IMDB movie reviews using Logistic Regression, SVM, and Random Forest.
# Sentiment Showdown: Logistic vs SVM vs RF 🎬🧠

This project performs **sentiment analysis** on the IMDB movie reviews dataset using classical machine learning models. It compares the effectiveness of **Logistic Regression**, **Linear SVM**, and **Random Forest** classifiers on text data.

## 📁 Dataset

- **Source**: [HuggingFace Datasets - IMDB](https://huggingface.co/datasets/imdb)
- **Content**: 50,000 labeled movie reviews (positive / negative)

## 🛠️ Models Compared

- ✅ Logistic Regression  
- ✅ Linear Support Vector Machine (SVM)  
- ✅ Random Forest Classifier  

## 🔍 Workflow

1. Load IMDB dataset using HuggingFace `datasets`
2. Preprocess text using TF-IDF vectorization
3. Train/test split (80/20)
4. Train and evaluate each classifier
5. Plot accuracy results and compare models

## 📊 Output

- Accuracy scores for all models
- Comparison visualization with seaborn
- Insights on model performance for binary text classification

## 🚀 Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ZohrehKeykhaee2025/sentiment-showdown.git
   cd sentiment-showdown
   ```

2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook مدل2.ipynb
   ```

## 📦 Requirements

```bash
pip install numpy scikit-learn matplotlib seaborn datasets
```

## 👤 Author

- **Zohreh Keykhaee**  
- GitHub: [ZohrehKeykhaee2025](https://github.com/ZohrehKeykhaee2025)

---

> If you enjoyed this project or found it helpful, don't forget to ⭐ the repo!
