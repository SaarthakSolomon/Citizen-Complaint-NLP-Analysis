# Citizen-Complaint-NLP-Analysis
# NLP Topic Modeling on Amazon Fine Food Reviews

This project focuses on using Natural Language Processing (NLP) techniques to extract key topics from unstructured customer reviews.

## 📊 Objective
To identify the most discussed themes in product reviews using:
- TF-IDF + NMF
- Bag of Words + LDA (with optimal K selection)

## 🧪 Dataset
**Amazon Fine Food Reviews**  
Source: [Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## ⚙️ Project Workflow
1. **Data Preprocessing**: Tokenization, stopword removal, lemmatization
2. **Vectorization**: TF-IDF & Bag of Words
3. **Topic Modeling**:
   - **NMF** for interpretable topics from TF-IDF
   - **LDA** for probabilistic topic generation
   - **Optimal K for LDA** determined using coherence score
4. **Visualization** of topics

## 🧠 Tools & Libraries
- Python 3.x
- Pandas, NumPy
- NLTK, Gensim, Scikit-learn
- Matplotlib, Seaborn
