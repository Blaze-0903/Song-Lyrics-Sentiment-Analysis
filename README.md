# 🎵 Sentiment Analysis of Billboard Song Lyrics using NLP

This project explores the emotional and thematic landscape of popular music by analyzing Billboard Top 100 song lyrics from 2012 to 2022 using Natural Language Processing (NLP) and AI techniques.

## 📌 Project Objective

- Clean and preprocess song lyrics data
- Perform feature extraction using TF and TF-IDF
- Cluster songs based on lyrical content
- Conduct sentiment analysis to determine emotional tone
- Visualize insights through word clouds and sentiment graphs

## 📂 Project Structure

```

.
├── Billboard\_Lyrics\_NLP\_Analysis.ipynb   # Main Jupyter notebook for analysis
├── billboard\_2012\_to\_2022\_top\_100\_song\_lyrics.csv  # Dataset used for the project
├── README.md

````

## 📊 Technologies & Libraries Used

- **Language**: Python
- **Libraries**: 
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for visualization
  - `nltk`, `wordcloud`, `TextBlob` for NLP
  - `scikit-learn` for vectorization and clustering

## 🔍 Key Features

- **Text Preprocessing**: Lowercasing, punctuation removal, stopword filtering, lemmatization
- **TF-IDF Vectorization**: Numerical representation of lyrics for machine learning
- **K-Means Clustering**: Groups similar songs into 5 thematic clusters
- **Sentiment Analysis**: Uses TextBlob to calculate polarity and subjectivity
- **Visualization**: Word cloud, cluster-wise sentiment analysis, and polarity distribution

## 💡 Insights

- Most frequent themes include **love**, **heartbreak**, **nightlife**, and **time**
- Sentiment analysis shows that a majority of songs lean toward neutral to positive sentiment
- Clustering reveals thematic groupings like party anthems, emotional ballads, and motivational tracks

## 📁 Dataset

The dataset used in this project includes song titles, artists, and lyrics from Billboard’s Top 100 songs from 2012 to 2022. It is publicly available and cleaned before use.


