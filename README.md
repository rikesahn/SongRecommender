# Song Recommender

a small app that asks a user to input a song title. 
if the song is not currently in the top 100 charts, the app will recommend a different but similar song from spotify to the user 

Python, BeautifulSoup, Spotipy, sklearn 

showcasing:
- webscraping Rolling Stones top 100
- using spotify API to get metadata for a database of recommendable songs
- using a k-means algorithm to cluster songs in the database according to similar metadata
- accepting user input of song title
- returning either a song from the top 100 of the same name, or a similar sounding song

