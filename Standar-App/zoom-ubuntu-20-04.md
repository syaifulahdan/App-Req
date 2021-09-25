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

2.Once the download is complete, install Zoom by running the following command as a user with sudo privileges:
<pre>
$ sudo apt install ./zoom_amd64.deb
</pre>

![alt img](https://github.com/syaifulahdan/App-Req/blob/main/Standar-App/Zoom-image/2-install%20zoom.png)

<pre>
mudaf@mudaf-Precision-7710:~$ sudo apt install ./zoom_amd64.deb
[sudo] password for mudaf: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Note, selecting 'zoom' instead of './zoom_amd64.deb'
The following additional packages will be installed:
  libegl1-mesa libgl1-mesa-glx libxcb-xtest0
The following NEW packages will be installed:
  libegl1-mesa libgl1-mesa-glx libxcb-xtest0 zoom
0 upgraded, 4 newly installed, 0 to remove and 6 not upgraded.
Need to get 16,8 kB/55,8 MB of archives.
After this operation, 232 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 /home/mudaf/zoom_amd64.deb zoom amd64 5.8.0.16 [55,8 MB]
Get:2 http://id.archive.ubuntu.com/ubuntu focal-updates/universe amd64 libegl1-mesa amd64 21.0.3-0ubuntu0.3~20.04.1 [6.456 B]
Get:3 http://id.archive.ubuntu.com/ubuntu focal-updates/main amd64 libgl1-mesa-glx amd64 21.0.3-0ubuntu0.3~20.04.1 [5.532 B]
Get:4 http://id.archive.ubuntu.com/ubuntu focal/main amd64 libxcb-xtest0 amd64 1.14-2 [4.804 B]
Fetched 16,8 kB in 1s (13,7 kB/s)         
Selecting previously unselected package libegl1-mesa:amd64.
(Reading database ... 190654 files and directories currently installed.)
Preparing to unpack .../libegl1-mesa_21.0.3-0ubuntu0.3~20.04.1_amd64.deb ...
Unpacking libegl1-mesa:amd64 (21.0.3-0ubuntu0.3~20.04.1) ...
Selecting previously unselected package libgl1-mesa-glx:amd64.
Preparing to unpack .../libgl1-mesa-glx_21.0.3-0ubuntu0.3~20.04.1_amd64.deb ...
Unpacking libgl1-mesa-glx:amd64 (21.0.3-0ubuntu0.3~20.04.1) ...
Selecting previously unselected package libxcb-xtest0:amd64.
Preparing to unpack .../libxcb-xtest0_1.14-2_amd64.deb ...
Unpacking libxcb-xtest0:amd64 (1.14-2) ...
Selecting previously unselected package zoom.
Preparing to unpack /home/mudaf/zoom_amd64.deb ...
Unpacking zoom (5.8.0.16) ...
Setting up libegl1-mesa:amd64 (21.0.3-0ubuntu0.3~20.04.1) ...
Setting up libxcb-xtest0:amd64 (1.14-2) ...
Setting up libgl1-mesa-glx:amd64 (21.0.3-0ubuntu0.3~20.04.1) ...
Setting up zoom (5.8.0.16) ...
run post install script, action is configure...
Processing triggers for mime-support (3.64ubuntu1) ...
Processing triggers for gnome-menus (3.36.0-1ubuntu1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.2) ...
Processing triggers for shared-mime-info (1.15-1) ...
Processing triggers for desktop-file-utils (0.24-1ubuntu3) ...
mudaf@mudaf-Precision-7710:~$
</pre>

You will be prompted to enter your password. That’s it. Zoom has been installed, and you can start using it.

![alt img](https://github.com/syaifulahdan/App-Req/blob/main/Standar-App/Zoom-image/3-open-zoom.png)

 
