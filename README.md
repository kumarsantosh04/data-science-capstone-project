# data-science-capstone-project
Capstone project: Churn prediction using pyspark

## Motivation
Churn prediction is an important problem in industry. It is not a surprise that old customers bring more revenue to a brand than a new custumer. Adding to that aquiring customer is equally costly. 

In this project I have made a model for churn prediction of a music company, 'Sparkify' which provides music streaming services. Since the amount of events generated by the users is enormous, using a distributed framework like spark will definetly aid the model development process. For that reason pyspark is used for analysis as well as model training and evaluation.

The results and findings are sumarized in this blogbost [here](https://medium.com/@kumarsantosh04/using-big-data-for-understanding-churn-in-the-music-streaming-industry-119c669e138).  You can also see the notebook [here](Sparkify.ipynb)


## Install requirements:

Run the following commands in the project's root directory to install dependencies

1. install [pyspark](https://medium.com/tinghaochen/how-to-install-pyspark-locally-94501eefe421) locally.
2. Install requirements using below command

~~~
pip install -r requirements.txt
~~~

Also install jupyter-notebook for running the Sparkify.ipynb.

## Instructions:

Run the following commands in the project's root directory.

~~~
jupyter-notebook
~~~       

http://localhost:8888 will open, open the Sparkify.ipynb and start running each cell one by one.

## Project Structure:
~~~
- Sparkify.ipynb
- README.md
- requirements.txt
~~~
## Project Components:
The analysis, modeling and evaluation is done in the ipynb.

## Acknowledgement

Udacity for providing the sparkify data.
