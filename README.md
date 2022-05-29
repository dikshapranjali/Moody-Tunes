# Project Description
It is a facial expression recognition-based movie and music suggestion web app that cheer up users and saves time while searching for a movie or song that matches their mood. The model is trained on the FER2013 dataset.
## Inspiration
Human beings are emotional creatures whose state of mind can usually be observed through their facial expressions. In today's world where everyone is striving for achievement, many people are succumbing to loneliness and anxiety as a result of this struggle.**Moody Tunes** is a quick fix for people to elevate their moods by recommending movies and songs based on their feelings.
## Features
- It recognizes facial expressions real-time based on the 6 categories i.e., angry, sad, fear, happy, surprise and neutral.
- Recommends a list of songs and movies to the user based on the captured facial expression
- On clicking on the movie which user wishes to watch, they will be redirected to IMDB website and for songs it redirects them to Spotify website.
- The user can navigate to the creator page by clicking on the creator button 
## Tech Stacks
- Keras
- Tensorflow
- Flask
- OpenCV
## Running the app
**Prerequisites**
- Setup a Virtual Env
- pip install flask
- Install the package pip install -r requirements.txt

**Running Flask**
- [ set MOODY TUNESS=app.py ]
- flask run
- Copy rhe http link and paste it on the browser to run the web app locally
## What's next for **Moody Tunes**
The next step is to improve the model's accuracy and connect the application to a database for getting an updated list of movies and songs each time the user expression is captured.
