# picnictube
Download searched Youtube videos comments by language without using the Youtube API

Based and inspired on [youtube-comment-downloader](https://github.com/egbertbouman/youtube-comment-downloader)

Added language detection for video title and comment

Added video search feature

Follow these steps:
```
python3 -m venv youtube

source youtube/bin/activate

pip3 install -r requirements.txt 

python comment_getter.py -q "league of legends" -l "tr"
```
Script creates ```[youtube-video-id].json``` files for each video when you run the it.

Json file contains:

```
{
"cid": "Ugy5pL3yXcvvUeopJJN4AaABAg", 
"text": "GARENN <3", 
"lang": "unknown", 
"time": "2 saat önce", 
"author": "Berkay Berkman", 
"votes": 0, 
"photo": "https://yt3.ggpht.com/a/AATXAJyY99STu49rLBisO-RIrrpnNeNcSXI1unE8jiHTqw=s48-c-k-c0xffffffff-no-rj-mo"
}
```
