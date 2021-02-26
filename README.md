# Topic Modeling Exploration of Stack Overflow Questions
## Goal
The goal of this project is to explore "helpful" questions on Stack Overflow using natural language processing and unsupervised learning. Filtering the public dataset hosted on Google Cloud Platform's BigQuery for the top 10% of questions by score, I used NLP and topic modeling techniques to identify topics most commonly discussed on the Stack Overflow site that were associated with questions users found most helpful.
## Methodology
1. Filtered data related to questions on Stack Overflow with the top 10% of scores associated with them, in addition to looking at posts with the 100 most-frequently used tags associated with them
2. Used NLTK pipeline to preprocess the text corpus of 140291 questions
3. Ran topic modeling on the corpus using CountVectorizer and TF-IDF for LDA and NMF
## Files Included
* [stackoverflow_questions_data_cleaning](https://github.com/wnobles/metis-project4-nlp/blob/main/stackoverflow_questions_data_cleaning.ipynb) notebook: data cleaning and preprocessing
* [stackoverflow_questions_eda](https://github.com/wnobles/metis-project4-nlp/blob/main/stackoverflow_questions_eda.ipynb) notebook: further data processing and EDA to remove stopwords
* [stackoverflow_questions_topic_modeling](https://github.com/wnobles/metis-project4-nlp/blob/main/stackoverflow_questions_topic_modeling.ipynb) notebook: topic modeling and data visualization
* [Metis Project 4 Presentation](https://github.com/wnobles/metis-project4-nlp/blob/main/Metis%20Project%204%20Presentation.pdf) pdf: final presentation for Metis program discussing the project in detail
