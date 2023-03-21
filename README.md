# Language-Detection
This project is an implementation of a language detection system using machine learning algorithms. The goal of this project is to classify text into different languages based on the input text.

## Getting Started
## Prerequisites
* Python 3
* scikit-learn
* numpy
* pandas

## Installation
Clone the repository:
$git clone https://github.com/yourusername/language-detection.git$
$cd language-detection$
Install the required packages:
$pip install -r requirements.txt$

## Usage
To use the language detection system, run the main.py file, $python main.py$ You will be prompted to enter a text string to classify. The system will output the predicted language of the text based on the machine learning model. You can also modify the code to classify a list of text strings or input from a file.

## Methodology

## Data Collection and Preparation
The language detection system was trained on a dataset of text in different languages. The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/basilb2s/language-detection?resource=download). The text was preprocessed to remove punctuation, numbers, and stopwords.

## Feature Extraction
The preprocessed text was transformed into a numerical representation using the bag-of-words model. The bag-of-words model represents text as a matrix of word frequency counts. The CountVectorizer function from scikit-learn was used to transform the preprocessed text into a matrix of word counts.

## Machine Learning Model
The multinomial Naive Bayes algorithm was used as the machine learning model for language detection. The multinomial Naive Bayes algorithm is a probabilistic algorithm that uses Bayes' theorem to predict the probability of a document belonging to a particular class. The algorithm was trained on the bag-of-words matrix and the language labels of the text.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
[Basil Saji](https://www.kaggle.com/datasets/basilb2s/language-detection?resource=download) for the language dataset.
