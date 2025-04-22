---
layout: default
title: "Spotify Clustering Recommendation System"
date: 2025-01-30
categories: Python
---

This project contains a recommedation system using a Spotify dataset. Within this project you will find that I applied clustering to the data to separate tracks based on similar audio features including danceability, energy, tempo, genre, and many others. Each cluster is intended to show a large distribution of popularity scores assigned to the tracks within them to ensure all artists and songs are being pushed equally. I incorporated many visuals displaying the differentiation between each cluster. 

The code for this project is available here: https://github.com/kennedineri/spotify-recommendation-system/blob/main/Spotify%20Recommendatins%20Project.ipynb

<p>Distribution of the clusters:</p>
<div style="width: 100%; margin-bottom: 20px;">
    <img src="https://github.com/kennedineri/spotify-recommendation-system/blob/main/cluster-images/PCA%20Clusters.png?raw=true" alt="Visualizing the clusters." style="width: 60%;">
</div>

<p>Distribuion of artists between the clusters:</p>
<div style="width: 100%; margin-bottom: 20px;">
    <img src="https://github.com/kennedineri/spotify-recommendation-system/blob/main/cluster-images/Artists.png?raw=true" alt="Number of artisits in the displayed clusters." style="width: 60%;">
</div>

<p>This violin plot emphasizes where the densest tracks of the indicated popularity score is along with the average popularity marked along the histogram inside each cluster plotted. Distribution of popularity scores within each cluster:</p>
<div style="width: 100%; margin-bottom: 20px;">
    <img src="https://github.com/kennedineri/spotify-recommendation-system/blob/main/cluster-images/Violin%20Plot%20of%20Popularity.png?raw=true" alt="Popularity score of tracks distributed across clusters." style="width: 60%;">
</div>

<p>Average value of audio features distributed among each cluster:</p>
<div style="width: 100%; margin-bottom: 20px;">
    <img src="https://github.com/kennedineri/spotify-recommendation-system/blob/main/cluster-images/Audio%20Feature%20Means.png?raw=true" alt="Audio feature distribution between clusters." style="width: 60%;">
</div>
