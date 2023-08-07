# Duplicate Question Pairs Checker (NLP Project)

**Team Size:** 4

## Table of Contents

- [Description](#description)
- [Key Skills](#key-skills)
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Feature Selection](#feature-selection)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributors](#contributors)
- [License](#license)

## Description

The **Duplicate Question Pairs Checker** is an NLP project that aims to develop a model capable of identifying duplicate pairs of questions in a given dataset. The project involves using natural language processing (NLP) techniques such as tokenization, stemming, and part-of-speech tagging to compare the semantic similarity between pairs of questions. By identifying duplicate question pairs, this project can have applications in various domains, including search engines, question-answering systems, and content recommendation platforms.

## Key Skills

- NLP (Natural Language Processing)
- Machine Learning
- Feature Selection
- Evaluation
- Data Cleaning

## Installation

To run the Duplicate Question Pairs Checker project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/aadithlasar/LPTESTQ.git
   cd duplicate-question-pairs
   ```

2. Set up a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset in a suitable format (CSV, JSON, etc.).

2. Preprocess the data using the provided data cleaning scripts (see [Data Cleaning](#data-cleaning)).

3. Implement and apply feature selection techniques (see [Feature Selection](#feature-selection)).

4. Train the duplicate question pairs identification model (see [Model Training](#model-training)).

5. Evaluate the model's performance (see [Evaluation](#evaluation)).

6. Use the trained model to identify duplicate question pairs in new datasets.

## Data Cleaning

Data cleaning is a crucial step to ensure the quality and reliability of the model. Various data cleaning techniques are applied to the raw data, including:

- Removing duplicate entries
- Handling missing values
- Text normalization (lowercasing, removing punctuation, etc.)

## Feature Selection

Effective feature selection is essential for building a robust model. Some feature selection techniques used in this project include:

- TF-IDF (Term Frequency-Inverse Document Frequency)
- Word embeddings (Word2Vec, GloVe, etc.)

## Model Training

The model is trained using a labeled dataset containing pairs of questions labeled as duplicates or non-duplicates. Techniques used during model training include:

- Creating a suitable training-validation split
- Building and training a deep learning or machine learning model
- Fine-tuning hyperparameters to improve performance

## Evaluation

Model performance is evaluated using appropriate evaluation metrics, such as accuracy, precision, recall, F1-score, and ROC curves. The evaluation process helps to determine the effectiveness of the model in identifying duplicate question pairs.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute, open issues, and submit pull requests to help improve this project!
