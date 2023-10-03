# Sentiment-analysis-of-product-reviews

Sentiment analysis is the use of natural language processing, text analysis, computational linguistics to systematically identify, extract, quantify, and study affective states and subjective information. Sentiment analysis is widely applied to materials such as reviews and survey responses, online and social media. The code in this repository performs sentiment analysis by classifying the product reviews using the TF-IDF measure and logistic regression. The final metric-value is about 98%.

## TF-IDF measure

This is a statistical measure of the importance of a word for a document in the collection, adjusted for the fact that some words are more frequently in general. The weight of a word is proportional to the frequency of use of that word in a document and inversely proportional to the frequency of use of the word in all documents in the collection.

The TF-IDF is the product of two statistics: term frequency and inverse document frequency.

A high weight in TF-IDF is reached by a high term frequency (in the given document) and a low document frequency of the term in the whole collection of documents.

To have more detailed explanations you can see the [article](https://en.wikipedia.org/wiki/Tf–idf).

## Build

### Cloning

Clone the repository from github by running the command in the terminal:
`git clone https://github.com/IlS0/Sentiment-analysis-of-product-reviews.git`.

### Requirements

Unzip the archive, navigate to the directory and install the requirements by running the following command:
`pip install -r requirements.txt`.

### Downloading the dataset

[Download](https://github.com/sismetanin/rureviews) the Sentiment Analysis Dataset for Product Reviews in Russian.

## Run

To run the notebook, the `main.ipynb` file and the dataset must be in the same directory. Also make sure you have Jupyter Notebook installed. You can see the installation guide [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html#installing-jupyter-using-anaconda-and-conda).