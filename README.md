# Monolingual Paraphrase Detection - Low Resource Sindhi Lang at Sentence Level
This project focuses on **sentence-level paraphrase detection for the Sindhi language**. The system classifies whether two Sindhi sentences convey the same meaning (paraphrase) or not (non-paraphrase).

## Overview

Paraphrase detection is important for many NLP applications such as question answering, plagiarism detection, information retrieval, and text similarity systems.
Most previous work focuses on English, while Sindhi remains a low-resource language. This project helps fill that gap by creating a dataset and building detection models.

## Objectives

* Build a Sindhi paraphrase corpus
* Train machine learning and deep learning models
* Compare different feature representations
* Develop a real-time prediction interface

## Dataset

* Collected Sindhi sentence pairs from online news sources
* Manually annotated into paraphrase and non-paraphrase
* Preprocessed and cleaned the text data
* Split into training and testing sets

## Methods Used

The following techniques were implemented and compared:

* N-gram features
* FastText embeddings
* Sentence Transformers
* Feature fusion approach

## Model Training

* Implemented in Python
* Used Scikit-learn and HuggingFace Transformers
* Experiments conducted on Google Colab
* Evaluated using standard classification metrics

## Results

* Feature fusion provided the best performance
* Sentence Transformers showed strong semantic understanding
* The system achieved reliable paraphrase classification for Sindhi text

*(You can add your exact accuracy/F1 score here.)*

## Web Interface

A simple web-based interface was developed where users can:

* Input two Sindhi sentences
* Get real-time paraphrase prediction

## How to Run

1. Clone the repository

```
git clone <your-repo-link>
cd <repo-folder>
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the model or notebook

## Tools & Technologies

* Python
* Google Colab
* Scikit-learn
* HuggingFace Transformers
* FastText
* Sentence Transformers

## Future Work

* Increase dataset size
* Improve model accuracy
* Deploy full web application
* Extend to other low-resource languages

## Author

**Maria**
Student Researcher – NLP / Low-Resource Languages
