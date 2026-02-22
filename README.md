# my-tgs-stic-comand
просто моя команда для создания стикеров тг

``` bash
ffmpeg -ss 00:05:51.35 -i "имя файла.mp4" -to 00:00:02.80 -an -c:v libvpx-vp9 -c:a libopus -crf 30 -vf "scale=512:-1" -b:v 500k "..\имя выходного файла.webm"
```
