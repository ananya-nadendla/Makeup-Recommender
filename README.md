# Makeup Recommender 👄💄

An NLP-based recommendation system that suggests alternative makeup products based on a user-selected item by capturing **deeper functional similarities** such as texture, finish, coverage, and key ingredients.

## Overview
This project focuses on recommending makeup products that *behave* similarly rather than simply matching shade or broad categories. Using natural language processing on product descriptions and ingredient lists, the system surfaces meaningful alternatives that share underlying functional qualities.

## Methods
- Preprocessed and normalized **4 makeup datasets** ([Sephora](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews), [Lip - Ulta, Eyes & Face - Amazon](https://app.beautyfeeds.io/sample_datasets))
- Extracted text features using **TF-IDF** on descriptions and ingredients
- Applied **Truncated SVD** for dimensionality reduction
- Grouped products using **K-Means clustering**
- Ranked recommendations via **cosine similarity** within clusters
- Visualized clusters using **PCA**
- Built an **interactive Jupyter-based UI** for product selection and recommendations

## Tech Stack
- Python  
- pandas  
- NumPy  
- scikit-learn  
- Jupyter Notebook  

## Authors
- **Ananya Nadendla**  
- **Gursimar Singh**  

## Notes
- 🎬[Demo Video](https://drive.google.com/file/d/1XWq9xp4_8eA7k-kYDWp83kZMVyUKDOKi/view)
- 📝[Final Project Report](https://drive.google.com/file/d/1CoDk9dZGf4PUg2nDa5Q_1i63FbnCAp9G/view?usp=sharing) for a more in depth analysis

