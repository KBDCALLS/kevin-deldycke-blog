---
date: 2006-08-22 01:18:25
title: Extract All Frames of a Video as Jpeg Images
category: English
tags: Linux, transcode, Video
---

You need to extract all frames of a video and save them as `.jpg` images files ? Transcode can do the job for you thanks to this command line:

    :::bash
    $ transcode -i video.avi -y im

Of course with some parameters tweaking you will be able to save images in any format.

Do this on little video only, else the number of generated files will be so huge that all your hard drive space will be eaten in a couple of minutes. Be carefull!
