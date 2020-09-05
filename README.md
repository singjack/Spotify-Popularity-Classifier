# Spotify-Popularity-Classifier
Collaborators: Nick Lee, Marc Jimenez

This is a Spotify classifier that uses machine learning in order to predict whether any given track on Spotify is considered popular or not based on various features of the songs.
In order to achieve this, we used data [from a database found on Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks) consisting of data from over 160,000 songs.

Features including acousticness, loudness, energy, danceability, etc. were all used in the classification process of whether or not a song is considered popular or not. We used the **Pandas** library in order to manipulate large dataframes.

### Example of features used to predict song popularity
![Img of Database](https://i.ibb.co/pdmNshn/Annotation-2020-09-05-132657.png)



After collecting all of our data, we then used **SciKitLearn** for all of our Machine Learning algorithms in order to train and predict our classification algorithm. 
Finally, we used **MatPlotLib** to create data visualizations in order for us to make better sense of our data and to find patterns in order to solve which features directly correlated with the popularity of any given song.

The rest of our findings including more extensive descriptions can be found in the Google Colab notebook found under the file entitled **Spotify_ML_Project.ipynb**
