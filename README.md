# Spotify-Genre-Prediction

Spotify has a really thorough and extensive  API which offers a lot of data on different tracks, genres, and artists. Spotify even provides human interpretable audio features for a given track; features such as "liveness", "mood", "loudness", etc. These features are computed from Spotify internal ML classification tools. 

The purpose of this project is to conduct a statistical analysis of such human interpretable audio features to infer track genre. The motivation behind this is that if these features do in fact capture the human interpretation of a song, then a track genre should be dependent on those features as track genre is, in theory, a classification of the track based upon human interpretation. 

With a simple multinomial statistical model, these features can predict track genre with a 72% accuracy. 

Spotify API reference: https://developer.spotify.com/documentation/web-api

Data scraping script: https://colab.research.google.com/drive/1VIpipujOuut-qT1iVkMw8lASIqxjEGDv?usp=sharing

See pdf for full project report. 


