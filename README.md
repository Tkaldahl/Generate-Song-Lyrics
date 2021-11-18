# Generate Song Lyrics

This project involves creating an ETL that allows all song lyrics to be scraped for a list of artists. It then allows potential duplicate songs to be flagged to streamline manual cleaning. From there, it allows a markov chain to be trained and stored as a dictionary for reference. 

Coming Changes
1. This project will eventually contain code to deploy the markov chain itself to flask, for a user to use. Unlike many similar projects, this markov chain will be trained on all artists songs, so allows the user to choose a list of artists will not be available. This is to better simulate how software engineering is used in a data science context, as opposed to webdev. 
