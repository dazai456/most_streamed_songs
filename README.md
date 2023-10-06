# Most Streamed Songs (All Time)
it's small db contains the 100 most streamed songs on Spotify with their Features Extracted using the Spotify API.

## Used tools
 1. excel (data cleaning)

### data cleaning log
1. combined the two tables by songs name using vlookup
2. converted data into table
3. removed duplicate value: (no duplicate found)
4. no odd or blank value found
5. trimed all text to make sure no extra spaces
6. change the column type to the proper one for each data (to avoid type errors) || power bi

### columns
- id: Unique ID given to each song on spotify
- name: name of the song
- streams: number of streams in billions
- realease_date: the release date of the song in fomrat (mm/dd/yyyy)
- duration: duration of the song in minutes
- energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
- key: The key the track is in. Integers map to pitches using standard Pitch Class notation.
- loudness: The overall loudness of a track in decibels (dB).
- mode:Mode indicates the modality (major or minor) of a track.
- speechiness: Speechiness detects the presence of spoken words in a track.
- acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic.
- instrumentalness: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context.

## Reference
- data source: https://www.kaggle.com/datasets/amaanansari09/most-streamed-songs-all-time/data