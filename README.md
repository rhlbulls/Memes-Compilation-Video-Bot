# Memes-Compilation-Video-Bot
A Python script that collects memes from Reddit and compiles them into a video. 
![image](https://user-images.githubusercontent.com/45164745/205436178-47c062f1-43ab-401f-845d-ffeba28af7d4.png)

## Steps to Follow

* Run the scraper.py python file after you clone the source code to start selenium scraping popular meme subreddits on Reddit.
* After that, a db.json file is used to store all of the links for posts. We may download the posts locally by using the RedDownloader library.
* The downloadedVideos directory is where the downloaded files are kept. Then, using MoviePy, photos are turned into 3-second videos that are combined with video memes and saved as final.mp4.
