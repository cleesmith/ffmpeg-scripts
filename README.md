# [FFmpeg](https://ffmpeg.org/) scripts

## My process for uploading videos to YouTube:

* shoot video(s) with GoPro Hero 4 Silver:
  * for every 17 minutes 44 seconds it creates a 4GB file
  * these need to be concatenated into one video
* use the proper script to process videos:
  * cls.one - for a single file video that's less than 4GB
  * cls.join - for a video comprised of 2 files
  * cls.join3 - for a video comprised of 3 files
* any script creates a single MP4 file called **output.mp4**
* usually this file is renamed to whatever is appropriate
* use HandBrake to compress and create a new MP4 file
* upload the compressed file to YouTube

> Typically, a 4GB will compress to around 1 GB, which uploads to YouTube much faster.

***
