# SpotifyPlaylistAnalysis
Analyze my own Spotify playlists and determine if there is a distinct difference between each of them.

The purpose of this project is below:



1. Work with Spotify API.
2. Perform Data Analysis and Modeling with novel data.



DataCollection.ipynb is focused on the collection (work with Spotipy wrapper library.
DataAnalysisAndModeling.ipynb is focused on performing data analysis and data modeling to answer the question: 
is there a discernable difference between each of my own playlist? Can we use data science to predict which song belongs in which playlist?



Due to Spotify's changes to their API, audio features are no longer accessible.
The following solution, although not ideal was used: find an old dataset with the songs and perform a merge with the available songs.
This means the songs in this analysis is not truly representative of all songs in my playlist; it is simply a (albeit biased) sample. 
We will (wrongfully, but out of necessity) assume this sample is random and fully representative of the population of all songs.



Data cleaning and analysis was performed. Scatterplots/boxplots/barplots were used to determine there was a disernable difference in songs between playlists.
Modeling (random forest with CV) was also performed. Although abnormally high, modeling indicated there is a discernable difference in songs between playlists.
