# ETL and Data Modeling with NoSQL (Cassandra) 

## Project overview
This repository is aimed to build an ETL pipeline using Python that extracts data from local JSON files and loads it into Apache Cassandra database running locally. In addition, data modeling was performed to ensure a smooth data flow through the pipeline.

### Assignment
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

They would like to have an Apache Cassandra database which can create queries on song play data to answer the questions. The goal is to create a database schema and ETL pipeline for this analysis. The database and ETL pipeline also should be tested by running queries given by the analytics team from Sparkify.

## Project description
The initial data screenshot is provided below:
![Initial data](/images/image_event_datafile_new.jpg)

The output of the project is designed according to the project's needs and answers the following questions (queries):
### Query 1
Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4

### Query 2
Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182

### Query 3
Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

## Running the project
### Pre-requisites
* Create a new virtual environment for the project (optional but highly recommended)
* Run 'requirements.txt' file to install dependencies for the project (pip install -r requirements.txt)

### How to run the project
Run 'etl.ipynb' as Jupyter notebook.
