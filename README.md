Convert a screencapture into a gif  
```
ffmpeg -i in.mov -pix_fmt rgb24 -r 10 -f gif - | gifsicle --optimize=3 --delay=9 > out.gif
```
