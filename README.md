# [FFmpeg](https://ffmpeg.org/) scripts

## How to upload videos to YouTube:

* shoot video(s) with **GoPro Hero 4 Silver**:
  * for every **17 minutes 44 seconds** it creates a **4GB file**
  * these need to be concatenated into one video
* use the proper script to process videos:
  * **cls.one** - for a single file video, i.e. it's 4GB or less
  * **cls.join** - for a video comprised of 2 files
  * **cls.join3** - for a video comprised of 3 files
* any script creates a single MP4 file called **output.mp4**
* usually **output.mp4** is renamed to something else
* then use **HandBrake** to compress and create a new MP4 file
* now upload the new MP4 compressed file to YouTube

### **Typically, a 4GB file will compress down to 1GB, which uploads to YouTube much faster.**

> The compression depends on the video content: does the background change a lot (i.e. your moving)
> which won't compress a lot, as oppose to a "head shot" video which does compress a lot.

***
