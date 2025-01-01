# Shinobi Pro
### (Shinobi Open Source Software)

Shinobi is the Open Source CCTV Solution written in Node.JS. Designed with multiple account system, Streams by WebSocket, and Direct saving to MP4. Shinobi can record IP Cameras and Local Cameras.

## Install and Use

- Installation : http://shinobi.video/docs/start
- Post-Installation Tutorials : http://shinobi.video/docs/configure
- Troubleshooting Guide : https://hub.shinobi.video/articles/view/v0AFPFchfVcFGUS

instalasi di armbian
```bash
sudo apt update
sudo apt upgrade -y
sudo apt install git -y
git clone https://github.com/ghozali25/Shinobi-CCTV.git
cd Shinobi
sudo chmod +x INSTALL/ubuntu.sh
sudo INSTALL/ubuntu.sh
```

- setting default saja semua dengan ketik perintah N <br>
- ketika muncul untuk PAM Library ketikan "cron"<br>
- ketika muncul setting mariadb lau pilih yes

jika selesai kita tinggal buka shinobinya dengan ketikkan pada browser
```bash
http://IP ADDRES LINUX:8080/super
```
kita bisa login ke super user dan membuat user baru, untuk masuk ku super user silahkan menggunakan id sebagai berikut
```bash
USERNAME : admin@shinobi.video
PASSWORD : admin
```


#### Docker
- Install with **Docker** : https://gitlab.com/Shinobi-Systems/Shinobi/-/tree/dev/Docker

## "is my camera supported?"

Ask yourself these questions to get a general sense.

- Does it have ONVIF?
    - If yes, then it may have H.264 or H.265 streaming capability.
- Does it have RTSP Protocol for Streaming?
    - If yes, then it may have H.264 or H.265 streaming capability.
- Can you stream it in VLC Player?
    - If yes, use that same URL in Shinobi. You may need to specify the port number when using `rtsp://` protocol.
- Does it have MJPEG Streaming?
    - While this would work in Shinobi, it is far from ideal. Please see if any of the prior questions are applicable.
- Does it have a web interface that you can connect to directly?
    - If yes, then you may be able to find model information that can be used to search online for a streaming URL.

Configuration Guides : http://shinobi.video/docs/configure

## Support the Development
Get a Mobile License to unlock extended features on the Mobile App as well as support the development!
- Shinobi Mobile App : https://cdn.shinobi.video/installers/ShinobiMobile/
- Get a Mobile License : https://licenses.shinobi.video/subscribe?planSubscribe=plan_G31AZ9mknNCa6z

## Links
- Documentation : http://shinobi.video/docs
- Features List : http://shinobi.video/features
    - Some features may not be listed.
- User Submitted Configurations : http://shinobi.video/docs/cameras
- Features : http://shinobi.video/features
