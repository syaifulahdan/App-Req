Zoom is not an open-source application, and it is not included in the Ubuntu repositories. We’ll install Zoom from their APT repositories.

1.Open your terminal and enter the following wget command to download the latest Zoom deb package:
<pre>
$ wget https://zoom.us/client/latest/zoom_amd64.deb
</pre>

![alt img](https://github.com/syaifulahdan/App-Req/blob/main/Standar-App/Zoom-image/1-wget-zoom.png)
<pre>
mudaf@mudaf-Precision-7710:~$ wget https://zoom.us/client/latest/zoom_amd64.deb
--2021-09-25 15:40:42--  https://zoom.us/client/latest/zoom_amd64.deb
Resolving zoom.us (zoom.us)... 52.202.62.202
Connecting to zoom.us (zoom.us)|52.202.62.202|:443... connected.
HTTP request sent, awaiting response... 302 
Location: https://cdn.zoom.us/prod/5.8.0.16/zoom_amd64.deb [following]
--2021-09-25 15:40:43--  https://cdn.zoom.us/prod/5.8.0.16/zoom_amd64.deb
Resolving cdn.zoom.us (cdn.zoom.us)... 54.192.13.243
Connecting to cdn.zoom.us (cdn.zoom.us)|54.192.13.243|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 55783248 (53M) [binary/octet-stream]
Saving to: ‘zoom_amd64.deb’

zoom_amd64.deb      100%[===================>]  53,20M   796KB/s    in 82s     

2021-09-25 15:42:05 (665 KB/s) - ‘zoom_amd64.deb’ saved [55783248/55783248]

</pre>
