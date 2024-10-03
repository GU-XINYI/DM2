# Data Mining: Advanced Topics and Applications

DM2 Project: [Datasets](datasets)  |  [Codes](scripts)  |  [Final report](report_final_Gu_Li.pdf)

Practical level of the Data Mining course, a project need to be created and presented that requires to analyze spotify datasets (tracks & artists), as well as a dataset of time series representing the spectral centroids of the song mp3 audio files, with different mining methods using python. And a written report need to be prepared showing the results of the project activity and the interpretation of the results found.


<p align="center">
  <img src="https://github.com/raivo-otp/issuer-icons/blob/master/vectors/spotify.com/spotify.svg" alt="Spotify Logo" width="200"/>
</p>

# Datasets
Datasets provided by the lecturers of the [course](http://didawiki.cli.di.unipi.it/doku.php/dm/start).

### _Tracks_
The Spotify Tracks dataset contains data concerning audio tracks (~100k records) accessible via the Spotify catalogue. These tracks span 114 distinct genres. Each track
is associated with some metadata such as _id_, _name_, _album_name_, and various musical characteristics such as _danceability_, _energy_, _duration_ms_ and _mode_.
### _Artists_
The Spotify Artists dataset provides information about artists. Each entry includes an _id_(a unique identifier for the artist), and the artist’s name. It also contains two numerical attributes: _popularity_, which ranges from 0 to 100, and _followers_, which indicates the number of followers. Additionally, the dataset includes a list of genres in which the artist is classified.
### _Time Series_
The time series dataset represents the spectral centroids of song MP3 audio files. It consists of 10,000 rows, corresponding to 20 distinct genres, with 500 rows per genre. Each time series has a length of 1,280 columns.

# Team members
- [Xinyi Gu](https://github.com/GU-XINYI)
- [Yian Li](https://github.com/Li-Yian)

# Tasks
- [Data Understanding & Preparation](./scripts/dm2_understanding.ipynb)
- [Time Series Analyses](./scripts/time_series): Understanding & Preparation · Clustering · Classification · Motifs & Shapelets · DeepLearning
- [Advanced Data-Preprocessing](./scripts/advanced_preprocessing): Imbalanced Learning · Dimension Reduction · Outlier Detection
- [Advanced ML & XAI](./scripts/advanced_ML_XAI):
  - Advanced Classification: Logistic Regression · SVC · Neural Networks · Ensamble Methods · Gradient Boosting
  - Advanced Regression: SVR · Random Forest
  - XAI: Lime
