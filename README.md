<div align="justify">
  
# Fake Reviews Detection

This repository is part of Post Graduation Research, which leverages machine learning algorithms and natural language processing techniques to detect fake reviews, ensuring authenticity in user-generated content.

This repository explores and compares various machine learning techniques for detecting fake reviews. It conducts a comparative study of four well-known machine learning models: Naive Bayes (NB), Support Vector Machine (SVM), Long Short-term Memory (LSTM), and Multi-layer Perceptron (MLP) using the Fake Reviews Dataset from Salminen.

- **Note:** Trained and Tested on TensorFlow version: 2.12.0 and Keras version: 2.12.0


## Full Research References
- **Title:** Detecting Fake Reviews Using Multiple Machine Learning Models: A Comparative Study
- **Contributors:** Akhandpratap Singh; Sachin Kumar
- **Abstract:** With the manifold growth of the e-commerce ecosystem in the last decade, online reviews are increasingly being viewed as a crucial factor in establishing and maintaining a positive reputation between customers and vendors. Further, reviews play an important and unbiased role in the decision making process for customers and a positive review for a targeted item usually draws a large number of customers and leads to significant rise in sales. These days, fake reviews are published on purpose to boost the company's virtual reputation and attract new customers. Due to which, detection of fake reviews is an active and emerging research topic. The purpose of this paper is to compare different machine learning techniques to detect fake reviews. For that purpose, a comparative study has been done among four well-known machine learning approaches namely Naive Bayes (NB), Support Vector Machine (SVM), Multi-layer Perceptron (MLP) and Long Short-term Memory (LSTM) on the Fake Reviews Dataset from Salminen. Among these, the Long Short-term Memory model provides the highest accuracy of 92% followed by Multi-layer Perceptron and Support Vector Machine.
- **Link:** https://doi.org/10.1007/978-981-19-7892-0_37

---
- **Title:** Fake Reviews Detection Using Multi-input Neural Network Model
- **Contributors:** Akhandpratap Singh; Sachin Kumar
- **Abstract:** The increasing penetration of the Internet and accessibility to smart devices in the last decade has led to new dimensions in the e-commerce ecosystem. The concept, of word-of-mouth in traditional marketing, is becoming obsolete, and a greater number of users are preferring reviews and ratings of a product before buying it online. With the increase in competition, e-commerce players and customers are hit by the new phenomenon of fake reviews, which are used to change customers’ sentiments and make businesses profitable. The global e-commerce industry is expected to cross USD 16,215.6 billion valuations by 2027 at a compound annual growth rate of 22.9%, which makes it extremely important to study fake reviews. So far, very limited work has been done in detecting fake reviews with the help of traditional machine learning models and limited datasets. This issue can be bridged up with the advancement in technology as new deep learning models and effective datasets have evolved. We have proposed a new model by combining the features of multilayer perceptron and LSTM, which provides the highest accuracy of 91.395%.
- **Link** https://doi.org/10.1007/978-981-19-8825-7_35

---

## Importing Libraries
- **Code:** Imports essential libraries like `pandas`, `numpy`, `nltk`, `sklearn`, `tensorflow`, and `matplotlib`.
- **Purpose:** Sets up the environment for data manipulation, visualization, NLP tasks, and machine learning.

---

## Data Loading
- **Code:** `pd.read_csv('reviews-dataset.csv')`
- **Purpose:** Loads the dataset into a DataFrame for analysis.
- **Dataset Link:** https://osf.io/tyue9

---

## License
MIT License.
</div>
