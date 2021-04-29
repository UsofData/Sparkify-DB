The purpose of this database is to provide the startup, Sparkify, with a way to record its data in an organised manner. 
A Star Schema was used here to simplify and speed up aggregations, so that the user does not have to wait a long time to find answers to their analytical questions.
Our schema consists of songplays as the fact table, as well as songs, artists, time and user as the dimension tables that connect to it.

2 types of files are used to record this information into our database: songs and logs. 
From song files, we record song and artist data, whereas from log files, we record time data and user data.
Finally, we query the song name, artist name and song duration to help us fill in our songplays fact table.