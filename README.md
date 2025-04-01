# Unsupervised Machine Learning with Python

This repository documents my application of KMeans clustering to a Spotify dataset containing 5,236 songs. The goal is to create musically meaningful clusters (playlists) and potentially automate playlist creation on Spotify. Detailed steps and outcomes are outlined in the notebook located in the "Script" folder.

## Objective
Can machine learning effectively replace human-curated playlists?

## Case Study
This project addresses a business case for Moosic, a startup currently relying on experts to curate playlists. Moosic aims to scale its operations and is exploring machine learning as a scalable alternative. Playlists generated should contain 50-250 songs each.

## Method
In my prototype, I implemented KMeans clustering using Quantile Transformer for data scaling. Additionally, I evaluated the impact of feature reduction via PCA.

## Conclusion
The prototype suggests that KMeans clustering presents a promising alternative for Moosic's scaling needs. Further optimization and testing are recommended.

## Files

### Data
spotify_5000_songs.csv: Dataset used for analysis

### Script
KMeans_clustering_music_playlists_prototype.ipynb: Notebook detailing the project steps

## Usage
1.	Save the dataset to your Google Drive or local machine.
2.	Update links within the notebook to reflect your storage locations.
3.	Explore and enjoy the music playlist samples generated in the notebook!

##Languages and Libraries
•	Python
•	Sklearn 
•	Pandas 
•	Matplotlib , Seaborn , Plotly

## Tool
•	Jupiter notebook 
