<h1 align="center"> VPN AutoScript Debian Stretch<img src="https://img.shields.io/badge/Version-1.3-blue.svg"></h1>

<p align="center">VPS AutoScript is made by FordSenpai to minimize the time consumed and user involvement in setting up your VPS</p>
<h3 align="center">Supported Linux Distribution</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Support-Debian%209-red.svg"></a>
  
</p>
<h3 align="center">Services</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Service-OpenSSH-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Dropbear-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Stunnel-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OpenVPN-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Squid3-green.svg"></a>
 </p>
<h3 align="center">Commands</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Commands-menu-yellow.svg"></a>
 </p>

<h3 align="center">Installation (DigitalOcean)</h3>

  ```html
wget https://raw.githubusercontent.com/johndesu090/AutoScriptDebianStretch/master/DebianStretch && chmod +x DebianStretch && ./DebianStretch
  ```

<h3 align="center">Installation (VULTR)</h3>

  ```html
wget https://raw.githubusercontent.com/johndesu090/AutoScriptDebianStretch/master/DebianStretchV && chmod +x DebianStretchV && ./DebianStretchV
  ```

<h3 align="center">Installation LEMP Stack Webserver</h3>

  ```html
wget https://raw.githubusercontent.com/johndesu090/AutoScriptDebianStretch/master/LEMP7 && chmod +x LEMP7 && ./LEMP7
  ```


<h3 align="center">Additional Info</h3>
<p align="center">
Recommended OS: Debian 9 Stretch x64

<h3 align="center">Screenshots</h3>
<p align="center">
<img src="https://github.com/johndesu090/AutoScriptDebianStretch/raw/master/Snapshots/1.png">
   </p>
  <p align="center">
  <img src="https://github.com/johndesu090/AutoScriptDebianStretch/raw/master/Snapshots/2.png">
   </p>
  <p align="center">
  <img src="https://github.com/johndesu090/AutoScriptDebianStretch/raw/master/Snapshots/3.png">
  </p>
  <p align="center">
  <img src="https://github.com/johndesu090/AutoScriptDebianStretch/raw/master/Snapshots/4.png">
   </p>
   
   <h3 align="center">ShadowsocksR (Optional)</h3>
   <p align="left">
   Download (Android): https://github.com/shadowsocksr-backup/shadowsocksr-android/releases
  
   Download (Windows): https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases
  
   Configuration file path: /etc/shadowsocks.json 
   
   Log file path: /var/log/shadowsocks.log 
   
   Installation directory: /usr/local/shadowsocks
   
   
   Installation:
   
```html
wget --no-check-certificate https://raw.githubusercontent.com/johndesu090/AutoScriptDebianStretch/master/ShadowR.sh
chmod +x ShadowR.sh
./ShadowR.sh 2>&1 | tee shadowsocksR.log
```
   Commands:
```html
Use the command:
Start: /etc/init.d/shadowsocks start 
Stop: /etc/init.d/shadowsocks stop 
Restart: /etc/init.d/shadowsocks restart 
Status: /etc/init.d/shadowsocks status
```

Facebook Support: https://www.facebook.com/johndesu090
   </p>
