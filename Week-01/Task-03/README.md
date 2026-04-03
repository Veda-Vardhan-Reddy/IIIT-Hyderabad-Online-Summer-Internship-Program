# Task 03 – Merge Audio and Video

## Audio Source
https://pixabay.com/music/main-title-nature-153630/

## Operations
- Trimmed the audio to 1 minute
- Merged the audio with Task 02 video using ffmpeg

## Final Video with Audio
https://youtu.be/UXdoHGnryvc

### Commands Used
ffmpeg -i nature.mp3 -ss 00:00:00 -t 00:01:00 trimmed_audio.mp3

ffmpeg -i final_video_task02.mp4 -i trimmed_audio.mp3 -shortest -c:v copy -c:a aac final_video_task03.mp4

### Final Video with Audio (YouTube Link)
https://youtu.be/UXdoHGnryvc

---

# Summary

| Task | Work Done | Output |
|------|-----------|--------|
| Task 01 | Extracted frames from `.webm` video | Frames Folder |
| Task 02 | Generated 1800 images + reconstructed video | final_video_task02.mp4 |
| Task 03 | Trimmed audio + merged with video | final_video_task03.mp4 |

---
