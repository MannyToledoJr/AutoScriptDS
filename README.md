<h1 align="center"> Premium AutoScript Debian Stretch<img src="https://img.shields.io/badge/Version-5.2.9-blue.svg"></h1>

<p align="center">VPN AutoScript is made by FordSenpai to minimize the time consumed and user involvement in setting up your VPS</p>
<p align="center">[Donations] GCASH: 09206200840 PAYPAL: johnford090@gmail.com FACEBOOK: John Ford Mangiliman</p>
<p align="center">Facebook Support Link: https://www.facebook.com/johndesu090</p>

<h3 align="center">Supported Linux Distribution</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Support-Debian%209-red.svg"></a>
  
</p>
<h3 align="center">Services</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Service-OpenSSH-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Webmin-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-BadVPN-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Dropbear-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Stunnel-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OpenVPN-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Squid3-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Privoxy-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-ShadowsocksR-green.svg"></a>
 </p>
<h3 align="center">Commands</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Commands-menu-yellow.svg"></a>
 </p>

<h3 align="center">Installation (Default Version)</h3>

  ```html
wget https://github.com/MannyToledoJr/AutoScriptDS/raw/master/DebianStretch && chmod +x DebianStretch && ./DebianStretch
  ```
<h3 align="center">Installation (N Version [old release])</h3>

  ```html
wget https://github.com/MannyToledoJr/AutoScriptDS/raw/master/DebianStretchN && chmod +x DebianStretchN && ./DebianStretchN
  ```

<h3 align="center">Installation OpenVPN-Monitor</h3>

  ```html
wget https://github.com/MannyToledoJr/AutoScriptDS/master/Files/Plugins/ovpnmonitor.sh && chmod +x ovpnmonitor.sh && ./ovpnmonitor.sh
  ```


<h3 align="center">Additional Info</h3>
<p align="center">
Recommended OS: Debian 9 Stretch x64

<h3 align="center">Screenshots</h3>
<p align="center">
<img src="https://github.com/johndesu090/AutoScriptDS/raw/master/Snapshots/1.png">
   </p>
  <p align="center">
  <img src="https://github.com/johndesu090/AutoScriptDS/raw/master/Snapshots/2.png">
   </p>
  <p align="center">
  <img src="https://github.com/johndesu090/AutoScriptDS/raw/master/Snapshots/3.png">
  </p>
  <p align="center">
  <img src="https://github.com/johndesu090/AutoScriptDS/raw/master/Snapshots/4.png">
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
wget --no-check-certificate https://github.com/MannyToledoJr/AutoScriptDS/master/Files/Plugins/SSR
chmod +x SSR
./SSR 2>&1 | tee shadowsocksR.log
```
   Commands:
```html
Start: /etc/init.d/shadowsocks start 
Stop: /etc/init.d/shadowsocks stop 
Restart: /etc/init.d/shadowsocks restart 
Status: /etc/init.d/shadowsocks status
```

   Multi Users; Config Setup:
```html
{
"server":"0.0.0.0",
"server_ipv6": "[::]",
"local_address":"127.0.0.1",
"local_port":1080,
"port_password":{
    "8989":"password1",
    "8990":"password2",
    "8991":"password3"
},
"timeout":300,
"method":"aes-256-cfb",
"protocol": "origin",
"protocol_param": "",
"obfs": "plain",
"obfs_param": "",
"redirect": "",
"dns_ipv6": false,
"fast_open": false,
"workers": 1
}
```

   </p>
