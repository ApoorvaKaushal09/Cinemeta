# Cinémeta

## [The-Movie-Recommender](https://cinemeta-recommender.herokuapp.com)

## Content-Based-Movie-Recommender-System-with-sentiment-analysis

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)



# [Here is the link to the live demo of my app(deployed app)](https://cinemeta-recommender.herokuapp.com)


This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

Don't worry if the movie that you are looking for is not auto-suggested. Just type the movie name and click on "enter". You will be good to go even though if you made some typo errors.


# This app contains movie dataset till the year 2020

## Similarity Score :
How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

## How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

## TODO:
Make the web application responsive for mobile screens

## How to run the project?

#### 1. Clone this repository in your local system.
#### 2. Download the credits.csv and movies_metadata.csv from [THE MOVIE DATASET FROM KAGGLE](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
#### 3. Install all the libraries mentioned in the [requirements.txt] file with the command 
```bash
pip install -r requirements.txt
```
#### 4. If you have problem installing the requirements then first set up a virtual environment and then install requirements
```bash
python -m venv venv
source venv/bin/activate (FOR mac)
```

#### 5. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command
```bash
python main.py
```
#### 6. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
#### 7. Hurray! That's it.
