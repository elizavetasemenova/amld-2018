Material for [the workshop at Appled Machine Learning Days 2018](https://www.appliedmldays.org/conf2018/workshop_sessions/machine-learning-for-news-theory-applications-and-visualisation-in-python.1): "Machine Learning for News: Theory, Applications and Visualisation in Python". Any content of this repository is subject to change both before and after the workshop.

## Getting started

1. Install Anaconda (miniconda would suffice)
2. Import the environment from the .yml file:

~~~
conda env create -f amld.yml
~~~

3. Activate the environment
~~~
source activate amld
~~~


## Downloading the dataset
~~~
cd data
curl https://www.dropbox.com/s/k16jptjyccxfdkn/clean_json.json?dl=0 -L -o clean_json.json
curl https://www.dropbox.com/s/20suwbl2l287r54/fulldatastuff.json?dl=0 -L -o fulldatastuff.json
curl https://www.dropbox.com/s/8oxuk3wg8fhtt8z/train_bodies.csv?dl=0 -L -o train_bodies.csv
curl https://www.dropbox.com/s/z6fqkr2v3qydzsb/train_stances.csv?dl=0 -L -o train_stances.csv
~~~

## Workshop structure 

Morning
1. Crash course in Python
2. Introduction to Natural Language Prcessing
3. Introduction to Neural Networks and Deep Learning

Afternoon
1. Wikileaks data processing
2. Wikileaks data visualization
3. Text to speech, Information retrieval, Text summarization, Deep Learning for fake news detection
