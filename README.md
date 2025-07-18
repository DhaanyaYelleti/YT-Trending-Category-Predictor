# 🎥 YouTube Trending Category Predictor

A mini Machine Learning project that predicts the trending category of a YouTube video based on its metadata.

---

## 📌 Project Overview

Here, we examine the connection between the category of a video and its corresponding category on the YouTube Trending dataset. We apply preprocessing steps and a Random Forest classifier to classify `category_id` based on available features.

---

## 📁 Dataset

Dataset: [USvideos.csv](https://www.kaggle.com/datasets/datasnaek/youtube-new)
The file contains metadata of US trending videos of YouTube including:

* Title
* Tags
* Views
* Likes
* Dislikes
* Comment count
* Channel title
* Category ID, etc.

---

## 🧠 ML Approach

* **Preprocessing**: Label encoding, elimination of irrelevant fields, management of missing values
* **Model**: RandomForestClassifier (scikit-learn)
* **Evaluation**: Classification report, feature importance

---

## 📊 Result

* Accuracy of class: Fairly good given class imbalance
* Feature importance identifies features that have most influence on category prediction

---

## 📎 Tech Stack

* Python 🐍
* Jupyter Notebook 📓
* scikit-learn
* pandas, matplotlib, seaborn

---

## 📝 Author

* Dhaanya Yelleti
* GitHub: [@DhaanyaYelleti](https://github.com/DhaanyaYelleti)

