# spotifycapstone
Springboard Capstone Project #1

PROBLEM

One of the most satisfying feelings is finding a new song you can’t stop listening to.  However, more likely than not, 
most songs people come across don’t align with their tastes.  A problem every fan of music runs into is finding artists 
or songs similar to what s/he already loves.  Now especially, when people have millions of songs waiting for them in an app, 
this problem turns what should be a relaxing/motivating/fun experience into a magnified inconvenience.

CLIENT

The client in this scenario would be anyone who has a Spotify account and would like to find new music recommendations 
based on what songs they’ve already listened to or have favorited.  Spotify has a similar user taste-based playlist, but 
for the sake of this project’s hypothetical situation the client would not have a music recommendation system in place in 
their app.  Using this model, they’ll be able to see what songs they might like without having to listen to them.

DATA

I will be pulling the data from the Spotify API with the help of the Python package made specifically for this, spotipy.  
With this API, I can view playlist and track features.


SOLUTION APPROACH

I will utilize two separate lists of songs to analyze: one list of songs I like, and the other list of songs I dislike.  
I will then extract the audio features of the songs (i.e. acousticness, liveness, loudness, tempo, etc.) and use these 
features to build a logistic regression model to classify a song as one I’d like or not.  I will use 80% of the data as 
training data, while the remaining 20% will be for testing.


IMPORTANT FILES
-Consolidated Report
-Deck
-Code
  - Data Wrangling
  - Data Story
  - EDA
  - In Depth Analysis

