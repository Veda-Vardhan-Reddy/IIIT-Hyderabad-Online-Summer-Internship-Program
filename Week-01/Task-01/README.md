# Task 01 – Frame Extraction

## Video Used
https://www.youtube.com/watch?v=tO01J-M3g0U

## Description
Extracted frames from the above YouTube video using ffmpeg.
Sample images are uploaded in this folder.

### Commands Used
yt-dlp -o "video.webm" https://www.youtube.com/watch?v=tO01J-M3g0U

ffmpeg -i video.webm -ss 00:00:15 -to 00:00:25 output_clip.webm

ffmpeg -i output_clip.webm -vf fps=2 clip_%04d.jpg

---
