# ssr.SlackBuild
SimpleScreenRecorder is a Linux program that I've created to record programs and games. 
SimpleScreenRecorder is a screen recorder for Linux. Despite the name, 
this program is actually quite complex. It's 'simple' in the sense
 that it's easier to use than ffmpeg/avconv or VLC :).
 ~~~
 this will grab the latest master from https://github.com/MaartenBaert/ssr
 ~~~
 This will also build your multi-lib for x86_64 with Alien Bobs multi-lib installed
 Whe build 32bit first on multilib.
 This is done to have final links to 64 bit.
 this requires 32bit ffmpeg and make sure you have 32bit dependencies
 when 32bit fails it will show the missing libraries. 
 ~~~
 Optional dependency:libav (libavformat, libavcodec, libavutil, libswscale)
 ~~~
 
 This requires:ffmpeg 
# For qt4 and qt5

