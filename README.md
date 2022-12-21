# flv

ffmpeg -stream_loop -1 -re -i "E:\FFOutput\BigBuckBunny-h265.mp4" -c copy -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny

ffmpeg -re -i "E:\FFOutput\BigBuckBunny-h265.mp4" -vcodec libx265 -acodec aac -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny

https://github.com/ksvc/h265webplayer

https://ks3-cn-beijing.ksyun.com/ksplayer/h265/mp4_resource/jinjie_265.mp4

ffmpeg -stream_loop -1 -re -i "E:\FFOutput\BigBuckBunny-h264.mp4" -vcodec libx265 -c copy -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny

http://192.168.2.29:8000/live/BigBuckBunny.flv
http://192.168.2.29:8000/live/BigBuckBunny.m3u8

ffmpeg -stream_loop -1 -re -i "E:\FFOutput\BigBuckBunny-h265.mp4" -c copy -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny

ffmpeg -re -i "E:\FFOutput\BigBuckBunny-h265.mp4" -c:a copy -c:v libx265 -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny

ffmpeg -re -stream_loop -1 -i "E:\FFOutput\BigBuckBunny-h265.mp4" -c:a copy -c:v h264 -f flv rtmp://192.168.2.29:1935/live/BigBuckBunny  推h264
