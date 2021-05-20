# NLP_Applications
The repository contains notebooks written in Python about NLP applications. The first folder created in this repository maintains the implementation of multi-label text classification on movies dataset. In the long term this repository will include hands-on applications and notebooks for various field of the NLP discipline.

## Table of Contents
### **Folder 1: Multi-label text classification**<br>
This folder serves as a mainting repository of the code used in my thesis title: *Movie Recommendation engine using an interactive conversational agent*. The code is updated regularly to Python, Tensorflow, Keras and other packages updates. The current version of the notebook are written in two Python environments.
* Parts 1, 2, 4, and 5 are written using Python 3.7.4 and 3.9.1
* Part 3 is the only part written in Python 3.6.9 because of the Tensorflow and Keras libraries.
* Tensorflow version 2.4.1
### Research & Development

Topics implemented in the first folder:
* Web scrapping using Python ```requests``` and ```BeautifulSoup``` modules.
* Web scrapping using the TMDB API using the ```tmdbv3api``` module.
* Data cleaning of text corpus.
* Stratified shuffle split of imbalanced datasets with multi-label dependent variable.
* Data tokenization for NLP applications using sklearn ```CountVectorizer``` and Tensorflow's ```Tokenizer```.
* Multi-Input & Multi-Output neural network development.
* Attention layer on text classification model.
* Neural network training and evaluation using various metrics from the Keras/Tensorflow and Sklearn libraries.
* Word embeddings extraction from the model classifier with the most accurate predictions.
* Identfying similar movies based on word embeddings and cosine distance/similarity.
* Movie recommendation algorithm in Python environment using Flask.

The folder contains only the notebooks and not the datasets used. Any third party or individual can check the code and use parts of the code as per the individual's needs. The datasets can be accessed upon request on this email: spanos.nikolaos@outlook.com

Please note that for using large parts of the notebooks it is advised to cite researcher's work using one of the following templates:

<ins>BibTex template</ins>
```latex
@misc{Spanos2021,
  author = {Spanos, Nikos},
  title = {Multi-label text classification on movies},
  year = {2021},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/NikosSpanos/NLP_Applications}},
}
````

<ins>Jupyter Notebook</ins><br>
Spanos Nikos, Multi-label text classification on movies, 2021, on Github https://github.com/NikosSpanos/NLP_Applications.

### Research & Development
* Apply Fourier layer from Tensorflow and assess its performance
* Create DJango application for the Dialogflow chatbot. At the moment the chatbot API functions through Facebook messenger.
