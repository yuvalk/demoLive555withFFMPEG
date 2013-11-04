demoLive555withFFMPEG
=====================
Writen by: Yuval Kashtan <yuvalkashtan@gmail>
2013-10-16

Demonstrate live555 RTSP with FFMPEG H264 support

Since I had many troubles finding a working example out there, I decided to create one.
I add SDL support just so you can see it working and used VLC to stream content to test it.

It is based off the test client supplied with Live555 on top of which I've added a modified version of Fabrice Bellard libavcodec/api-example.c.

HOW TO COMPILE
-----------------
you'll have to modify the Makefile to fit your location of ffmpeg and live555 (and SDL)

HOW TO COMPILE ON WINDOWS
--------------------------
you'll have to organize the pre-requesits under ReferenceLib on your own (the names of the directories are all in the .vcxproj file)
then you can compile with Visual Studio

KNOWN LIMITATIONS:
-------------------
This is not a fully working client!
merly a quick demo 

- for now, you'll have to manually set the width and height in the code

