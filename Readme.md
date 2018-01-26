Material for [the workshop at Appled Machine Learning Days 2018](https://www.appliedmldays.org/workshop_sessions/machine-learning-for-news-theory-applications-and-visualisation-in-python): "Machine Learning for News: Theory, Applications and Visualisation in Python". Any content of this repository before 27th January 2018 is subject to change.

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
curl https://www.dropbox.com/s/ukifanl57wzp7cj/datajson_sample.json?dl=0 -L -o dataset.json
~~~
 
