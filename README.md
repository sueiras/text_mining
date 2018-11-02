# Text Mining

Exercises for the Text Mining course

- 01 NLP whit NLTK
- 02 Text classification whit Sklearn
- 03 Word representations whit Gensim
- 04 RNN whit Keras
  - Sentiment model
  - Word tagging
- 99 Homework



# Instructions to use the AWS environment

https://github.com/sueiras/training/blob/master/docs/aws.md

https://github.com/sueiras/training/blob/master/docs/install_tensorflow_ubuntu_aws.md

### AWS AMI for this course:
- region: Ireland
- AMI id: ami-032d465c3dcc16326
- Name: sueiras-test-mining



# Anaconda environment

1.- Install anaconda3 last version. All default options.

2.- Start an Anaconda terminal and execute...

```
# Install jupyter extensions 
conda install anaconda-nb-extensions -c nb-conda

# Create environment and install text mining packages
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


# Download the next linguistic resources from the web and unzip in the data directory:
  - [aclImdb corpus (41Mb)](https://s3-eu-west-1.amazonaws.com/text-mining-course/aclImdb.zip)
  - [Sentiment corpus (65Mb)](https://s3-eu-west-1.amazonaws.com/text-mining-course/sentiment_corpus.zip)
  - [ATIS database](https://s3-eu-west-1.amazonaws.com/text-mining-course/atis.zip)
  - [Glove embeddings (134Mb)](https://s3-eu-west-1.amazonaws.com/text-mining-course/glove.6B.100d.txt.zip)
  - [Lexvec embedings (398Mb)](https://www.dropbox.com/s/kguufyc2xcdi8yk/lexvec.enwiki%2Bnewscrawl.300d.W.pos.vectors.gz)
