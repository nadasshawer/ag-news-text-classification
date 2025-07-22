# AG News Text Classification
This project is part of my NLP internship with Elevvo Pathways, focusing on multi-class text classification using the AG News dataset. The goal was to build a pipeline that classifies news articles into four categories based on their content. I used a traditional machine learning approach, applying TF-IDF vectorization and training a logistic regression model for classification.

The workflow included loading and exploring the dataset, preprocessing the text (lowercasing, removing special characters, stopword removal, and lemmatization), transforming the text into numerical features using TfidfVectorizer, and training a LogisticRegression model from Scikit-learn. I also evaluated the model’s performance using accuracy, classification report, and confusion matrix, and visualized the top 10 most frequent words per category using Seaborn bar plots.

The project highlights key NLP steps like data cleaning, vectorization, supervised model training, evaluation, and visualization. All work was done in Python using libraries including Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn, and tqdm.

📂 Due to file size limits, the dataset is not included in this repo.

🔗 Download AG News Dataset:
https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset
