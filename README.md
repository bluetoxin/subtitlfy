# subtitlfy

**subtitlfy** is a lightweight utility for creating subtitles.

## Installation   

First, make sure you have "ffmpeg" installed. Then install this tool using PIP:  
```
pip install subtitlfy
```

## Usage
```
subtitlfy -t "Hello World" -v "$(pwd)/a.mov" -s
```
| Flag| Meaning                     | Type    |  Example       |
| ----|:---------------------------:|:-------:|:--------------:|
| -t  | Text for subtitles          | "text(str)" or "start(int),end(int),text(str);start(int),end(int),text(str)" | "Text here!" or "0,1,First;1,2,Second" |
| -v  | Video for subtitles         |  path_to_videofile(str)    | $(pwd)/example.mov|
| -s  | Force a file to be replaced |    -     | - |

## Licence   
<p> This software is under BSD License.</p>  
