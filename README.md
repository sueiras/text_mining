# Text Mining

Exercises for the Text Mining course

- 01 NLP whit NLTK
- 02 Text classification whit Sklearn
- 03 Word representations whit Gensim
- 04 RNN whit Keras
  - Sentiment model
  - Word tagging
- 99 Homework



# Instructions to use Google colab

Open google colab


To make changes and save it the best optios are fork the repository and 



# OPTIONAL: Create a local Anaconda environment and install text mining packages

Note: To install spacy you need administrator privileges. If not, check 


Open an Anaconda terminal and execute

```
conda create -n tm python=3.6
activate tm

conda install pip

conda install graphviz
conda install pandas scikit-learn
conda install -c anaconda jupyter 
conda install matplotlib
conda install pillow 
conda install -c conda-forge spacy

# Spacy models (37.4Mb - 36.7Mb - 120.8Mb)
python -m spacy download en
python -m spacy download es
python -m spacy download en_core_web_md

pip install --upgrade gensim
pip install h5py
pip install pydot-ng
pip install nltk
pip install pyldavis

pip install --ignore-installed --upgrade tensorflow 

```


# OPTIONAL: To execute notebooks in local download the next linguistic resources from the web and unzip in the data directory:
  - [aclImdb corpus (41Mb)](https://s3-eu-west-1.amazonaws.com/text-mining-course/aclImdb.zip)
  - [Sentiment corpus (65Mb)](https://s3-eu-west-1.amazonaws.com/text-mining-course/sentiment_corpus.zip)
  - [ATIS database](https://s3-eu-west-1.amazonaws.com/text-mining-course/atis.zip)
  - [Glove embeddings (134Mb)](https://s3-eu-west-1.amazonaws.com/text-mining-course/glove.6B.100d.txt.zip)
  - [Lexvec embedings (398Mb)](https://www.dropbox.com/s/kguufyc2xcdi8yk/lexvec.enwiki%2Bnewscrawl.300d.W.pos.vectors.gz)
