# Text Mining

Exercises for the Text Mining course

- 01 NLP whit NLTK
- 02 Text classification whit Sklearn
- 03 Word representations whit Gensim
- 04 RNN whit Keras
  - Sentiment model
  - Word tagging
- 99 Homework


# Anaconda environment

- Install anaconda. 
  - Optional, install jupyter extensions
  ```
  conda install conda_nb
  ```  	
- Create the environment

```
conda create -n tm python=3.5
source activate tm

conda install graphviz
conda install pandas scikit-learn
conda install jupyter
conda install matplotlib
pip install h5py
pip install pydot-ng
pip install nltk
pip install --upgrade gensim
pip install --ignore-installed --upgrade tensorflow
pip install keras
```

- Download resources from NLTK data

```
import nltk 
print(nltk.data.path)# Check the nltk_data path
nltk.download('punkt')
nltk.download('brown')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
nltk.download('tagsets')
nltk.download('wordnet') 
```

- Download the next linguistic resources from the web
	- Stanford NLP resources: 
		- Core NLP (372Mb): [http://nlp.stanford.edu/software/stanford-corenlp-full-2017-06-09.zip]()
		- English models (991Mb): [http://nlp.stanford.edu/software/stanford-english-corenlp-2017-06-09-models.jar]()
		- Spanish models (203Mb): [http://nlp.stanford.edu/software/stanford-spanish-corenlp-2017-06-09-models.jar]()
	- Lexvec embedings (398Mb): [http://nlpserver2.inf.ufrgs.br/alexandres/vectors/lexvec.enwiki%2bnewscrawl.300d.W.pos.vectors.gz]() 
	- Glove embedings (822Mb): [http://nlp.stanford.edu/data/glove.6B.zip]()
