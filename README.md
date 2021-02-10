
# youtube-playlist-downloader
A simple script to download entire youtube playlist in 360p or 720p.
Made with Python3 <3
**Not actively maintained**

> NOTE: I do not encourage to download any copyright content from Youtube, this script is for educational purpose only.



# Usage
<ul>
    <li>open cmd and cd to the folder where this script is present</li>
    <li>type - python ytdown.py</li>
    <li>Press Enter and Enjoy!</li>
</ul>

![alt text](https://image.ibb.co/eimJUn/uplod.jpg)

# Features
<ul>
    <li>Download videos various resolution like 360p or 480p</li>
    <li>Starts from the previous state</li>
    <li>Get notified when download is finished</li>
    <li>Get details about the download size of video</li>
</ul>


# Requirements
<ul>
    <li>requests (pip install requests)</li>
    <li>pytube (pip install pytube)</li>
    <li>youtube-dl (pip install youtube-dl)</li>
</ul>


# Finally
I want to thank the developers of the amazing pytube package powers my script to run efficiently in dowloading entire playlist of a channel.


# Video
If you would like to watch a video tutorial then <a href='https://www.youtube.com/watch?v=Sk4PlD1pAdg&t=4s' target='_blank'>Click Here</a><br>


# How it works?
At its core we are using Pytube to download videos, i wrote this script when downloading playlist was not inbuilt in pytube, so we fetch the list of videos from playlist page and download them in sequence.

