```
sudo apt-get install mplayer2 caca-utils
sudo wget -qO /usr/local/bin/youtube-dl https://yt-dl.org/downloads/latest/youtube-dl
sudo chmod a+rx /usr/local/bin/youtube-dl
youtube-dl -o- "https://www.youtube.com/watch?v=9W_ViVlbUw0" | mplayer -vo caca -
```
