# flv

nodejs 推流 h265 

推h264
ffmpeg -re -stream_loop -1 -i "E:\FFOutput\BigBuckBunny-h265.mp4" -c:a copy -c:v h264 -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny  

h265
ffmpeg -stream_loop -1 -re -i "C:\Users\qiaoj\Documents\Videos1409899.mp4" -vcodec libx265 -c copy -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny
