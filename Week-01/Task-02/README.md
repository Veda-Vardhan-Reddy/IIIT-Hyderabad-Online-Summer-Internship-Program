# Task 02 – Reconstruct 1-Minute Video

## Description
Generated 1800 Images (30 fps × 1 minute).
Reconstructed them into a 1-minute video using ffmpeg.

## Final Video
https://youtu.be/WnMm532bJgo

### Commands Used
ffmpeg -i output_clip.webm -vf fps=30 generated_images/img_%04d.jpg

ffmpeg -framerate 30 -i generated_images/img_%04d.jpg -c:v libx264 -pix_fmt yuv420p final_video_task02.mp4

### Final Video (YouTube Link)
https://youtu.be/WnMm532bJgo

---
