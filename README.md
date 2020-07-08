# picnictube
Download searched Youtube videos comments by language without using the Youtube API

Based and inspired on [youtube-comment-downloader](https://github.com/egbertbouman/youtube-comment-downloader)

Added language detection for video title and comment

Added video search feature

Follow these steps:
```
python3 -m venv youtube

source youtube/bin/activate

python comment_getter.py -q "league of legends" -l "tr"
```
