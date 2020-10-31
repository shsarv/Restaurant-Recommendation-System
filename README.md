# Restaurants Recommendation System
This repository contains code for Recommendation of differents restaurants. Developed using Flask and python. Website is hosted on heroku.
It's live at https://restaurants-spotter.herokuapp.com/  .


### Structure

The directory contains web sub directories and a sub directory for hosting model and other scripts:

1. [app.py](https://github.com/shsarv/Restaurant-Recommendation-System/blob/main/app.py)The file which contains all the main backend operations of the website and used to run the flask server locally.
   
2. [Procfile](https://github.com/shsarv/Restaurant-Recommendation-System/blob/main/Procfile) for setting up heroku.

3. [requirement.txt](https://github.com/shsarv/Restaurant-Recommendation-System/blob/main/requirements.txt) contains all the dependencies.

4. [templates](https://github.com/shsarv/Restaurant-Recommendation-System/blob/main/templates) contains the html file.

5. [static](https://github.com/shsarv/Restaurant-Recommendation-System/blob/main/static) contains the css file and images.
  
### Codebase

The entire code has been developed using Python programming language and is hosted on Heroku. The analysis and model is developed using SkcitLearn library. The website is developed using Flask. 

### How to run the project:

  1. Open the `Terminal`.
  2. Clone the repository by entering `https://github.com/shsarv/Restaurant-Recommendation-System.git`.
  3. Ensure that `Python3` and `pip` are installed on the system.
  4. Create a `virtualenv` by executing the following command: `virtualenv env`.
  5. Activate the `env` virtual environment by executing the follwing command: `source env/bin/activate`.
  6. Enter the cloned repository directory and execute `pip install -r requirements.txt`.
  7. Now, execute the following command: `flask run` and it will point to the `localhost` server with the port `5000`.
  8. Enter the `IP Address: http://localhost:5000` on a web browser and use the application.
  
### Dependencies

The following dependencies can be found in [requirements.txt](https://github.com/shsarv/Restaurant-Recommendation-System/blob/main/requirements.txt):

  1. [scikit-learn](https://scikit-learn.org/)
  2. [Flask](https://palletsprojects.com/p/flask/)
  3. [pandas](https://pandas.pydata.org/)
  4. [numpy](http://www.numpy.org/)
  5. [scikit-learn](https://scikit-learn.org/stable/index.html)
  6. [gunicorn](https://gunicorn.org/)
  
### Cosine Similirity is used for recommendation purpose using Scikit-learn library.

### References
#### For Building machine learning model and deployment:
1. https://medium.com/the-andela-way/deploying-a-python-flask-app-to-heroku-41250bda27d0
2. https://scikit-learn.org/stable/modules/generated/sklearn.metrics.pairwise.cosine_similarity.html
3. https://www.machinelearningplus.com/nlp/cosine-similarity/
4. https://towardsdatascience.com/cosine-similarity-how-does-it-measure-the-similarity-maths-behind-and-usage-in-python-50ad30aad7db
5. https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/
6. Machine Learning course- https://www.coursera.org/learn/machine-learning/


### License



### Thanks for visiting! 🌸


<hr>

<img src="https://img.shields.io/github/followers/shsarv?style=social"><img src="https://img.shields.io/twitter/follow/sarveshroli?label=twitter&style=social">
