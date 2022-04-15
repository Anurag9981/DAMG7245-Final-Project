# Content based Music Recommendation System

![image](https://user-images.githubusercontent.com/13203059/163527232-91f5d9e5-7bd0-4ca4-a251-c22e0419876e.png)


# CLaaT Document

[Access the Claat document here](https://codelabs-preview.appspot.com/?file_id=1O_eeM-wOY7rFtn7uUnLgebKkyjFOC_nIrbewg-zlcqQ#10) 🚀

# Overview 📝

We use automated recommender systems everywhere in our day-to -day lives,be it the TV show to binge watch on Netflix, playlists on Youtube or Job recommendations on LinkedIn. In the same space we have recommender systems in music applications as well - Spotify, FreeSound,Songkick to name a few. As part of an academic project for course Big Data Systems & Intelligence Analytics we will build a data pipeline based on a similar idea, wherein we will use pre trained model inference to suggest users recommended music playlists that suit their interests.

# Goals 🎯
Our objective is to build an application where  users will be able to provide a link to their music playlist and get relevant content based recommendations from our pre-trained Machine learning model. Features that are planned to be implemented around this recommendation system pipeline are as follows - 

💡 Users can have the option to get recommendations based on selected genres from a dropdown. The results for which are fetched from a cached system that gets Top 50 songs from Open Source Music APIs(Last.FM, Spotify, SongKick, SoundCloud etc) on a daily basis.

💡 Using recently searched songs data of User, users would receive Email 📧 music recommendations on a weekly basis. 

💡 Create a fingerprint from audio files stored in cache and recognize them as as user tries to play a song.

💡 Implement User analytics Dashboard to account for the following - Word cloud, playlist recommendation feedback(like/dislike), Most popular genres among users, last activity etc.


# Use cases 📑

By creating veracity and options for Music listeners and analyzing their listening patterns, 
A Music Recommendation system like ours can be integrated/shared with social media platforms like Instagram and snapchat to search for similar songs based on the user input.


# Dataset Source 🔦

Spotify Million playlist dataset : AIcrowd | Spotify Million Playlist Dataset Challenge | Challenges
The dataset contains 1,000,000 playlists, including playlist titles and track titles, created by users on the Spotify platform between January 2010 and October 2017.It has 1 million Spotify playlists, over 2 million unique tracks, and nearly 300,000 artists.

# Process Outline

1. Data Preprocessing 
2. Understanding the Dataset - Exploratory Data Analysis(EDA)
3. Building a pipeline system using pretrained model and also using various tools/softwares(AWS Sagemaker, Airflow, Streamlit, GCP)
4. Deploying the model on AWS
5. Build a web application using streamlit for showcasing the results.


Milestones


Time Frame

Day 1 - 5
Data processing, EDA, Model selection

Day 5 - 10
Deployment of Models, Setup of Data pipeline, Streamlit Integration

Day 10 - 15
System integration, Testing and documentation

# Deployment Details

Language : Python
Container : Docker
Cloud Tools : Google Cloud Storage, Amazon Web Services
Tools for Analysis : Visual Studio code.
Streamlit, airflow


# Architecture

![image](https://user-images.githubusercontent.com/13203059/163527558-f0e7b54c-0ea8-4693-ab89-fbeb00472c9d.png)


# User Interface Design Plan

User Interface will be built using Streamlit and deployed on streamlit cloud.

![image](https://user-images.githubusercontent.com/13203059/163527610-3868cb59-a79f-4d8c-abb1-bd860f2eac22.png)

# Reference 

[How to build a music recommender system. | Towards Data Science](https://towardsdatascience.com/how-to-build-an-amazing-music-recommendation-system-4cce2719a572)

[Music Recommender System (iitk.ac.in)](https://www.cse.iitk.ac.in/users/cs365/2014/_submissions/shefalig/project/)

[Music APIs - A List of Free and Public APIs (the-api-collective.com)](https://the-api-collective.com/category/music)

[AIcrowd | Spotify Million Playlist Dataset Challenge | Challenges](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)







