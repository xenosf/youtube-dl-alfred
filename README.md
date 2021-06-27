
# Youtube Downloader Alfred Workflow
Alfred workflow for quickly grabbing video/audio off YouTube using [youtube-dl]((https://github.com/ytdl-org/youtube-dl)).

## Why?
I got too lazy to keep opening Terminal and typing in the command :D

## Requirements
* Alfred Powerpack (Tested on Alfred v4.3.4)
* [youtube-dl](https://github.com/ytdl-org/youtube-dl)
* ffmpeg (if saving as audio)

## Setup
1. Add workflow to Alfred.
2. Set variables:
    * `download_path`: **absolute path** of the directory you want your files to be saved to.
    * `youtubedl_location`: **absolute path** of your youtube-dl directory (can be located by running `which youtube-dl` in a terminal emulator)
## Usage
```
ytdl <link>
```
Then select the option you want.

### Video
![Demo of 'video' option](https://user-images.githubusercontent.com/40383042/123552342-452d3400-d7a8-11eb-9dd5-11f1c6971f2f.gif)

<img width="349" alt="Screenshot 2021-06-28 at 00 26 39" src="https://user-images.githubusercontent.com/40383042/123552347-4a8a7e80-d7a8-11eb-888a-330479c0a0dd.png">



### Audio
![Demo of 'audio' option](https://user-images.githubusercontent.com/40383042/123552328-3a729f00-d7a8-11eb-898a-060bde5c5e65.gif)

<img width="348" alt="Screenshot 2021-06-28 at 00 26 33" src="https://user-images.githubusercontent.com/40383042/123552350-4cecd880-d7a8-11eb-9fa3-fc7063a3c25d.png">


## Footnote
In my 5 minute internet search for an icon to put in this, I found [this abomination](https://icon-icons.com/es/icono/entre-nosotros-youtube/156933). Enjoy:

![Amogus Youtube Icon](https://cdn.icon-icons.com/icons2/2619/PNG/256/among_us_youtube_icon_156933.png)

