This is a simple recommender system that suggests songs based on audio feature similarity. You pick a song, and the system finds other tracks that feel kinda similar according to Spotify’s audio features.

The dataset comes from Kaggle and contains info on 30,000+ Spotify songs with features like:

    danceability, energy, valence, tempo, acousticness, instrumentalness, speechiness, liveness, loudness

Basically, the system tries to measure how close songs are in this feature space and gives you recommendations.

**Dataset Link:** [30,000 Spotify Songs on Kaggle](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs?select=spotify_songs.csv)

## Limitations 🙃

    - Right now, you can only search by song name (no artist filter yet).
    - Its case-insensitive, so no worries about capital letters.
    - If you typo a bit, it’ll try to give you some close matches.

Also.. if there are multiple songs with the same name by different artists, it just picks the first one it finds.

Super simple micro project, more like a playground to mess around with recommender systems. But hey, it works 😅
