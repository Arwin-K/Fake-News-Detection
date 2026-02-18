# Fake-News-Detection

## Project Overview
This project implements a Natural Language Processing (NLP) pipeline to detect and classify news articles as fake or real using supervised machine learning and deep learning techniques. The system processes raw textual data, transforms it into numerical representations, and applies multiple classification models to evaluate performance across different algorithmic approaches.

The project is implemented as a single Jupyter Notebook (.ipynb) and is designed to be reproducible, modular, and extensible for future research in misinformation detection and automated content moderation.

The primary objectives of this project are:

* To build an end-to-end fake news detection pipeline
* To compare traditional machine learning models against transformer-based deep learning models
* To evaluate model robustness, accuracy, and generalization capability
* To provide a foundation for future real-time misinformation detection systems

## Machine Learning Workflow 
### Data Preprocessing
All raw data undergoes these preprocessing techniques, removing irrelevant noise and reducing dimensionality to increase model efficiency. 
* Lowercasing Text
* Regex Cleaning
* Stopword Removal
* Lemmatization

### Feature Engineering 
#### TF-IDF Vectorization
* Lightweight and effective within the use cases for lightweight Machine Learning models
#### Contextual Embeddings 
* More heavyweight with the use of pre-trained models and denser vectorization for each word, resulting in longer processing times

## Dataset Description 
The dataset used for this project is shown here: https://www.kaggle.com/datasets/aadyasingh55/fake-news-classification/data
### Dataset Characteristics
| Column     | Description           |
| ---------- | --------------------- |
| title      | News article headline |
| text       | Full article content  |
| label      | Fake (0) or Real (1)  |




