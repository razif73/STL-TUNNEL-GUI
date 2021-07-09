# xderm-mini_GUI Openwrt

### Information
xderm-mini GUI is OpenWrt software by @ryanfauzi1 which can help you to inject your connection using VPN injection (SSH/Trojan/Vmess)

WebUI Page : http://192.168.1.1/xderm

Default ```auth.txt``` (WebUI Login Information)
```
Username  : admin
Password  : xderm
```

Default ```config.txt```
```
host=103.157.1xx.xx
port=443
pudp=7300
user=ryanxxxx
pass=123xxx
sni=www.xxx.xx
vmess://eyJhZGQiOixxxxxxx
mode=0
```

### Installation
Main Xderm-Mini Installation
```
wget -O installer https://raw.githubusercontent.com/ryanfauzi1/xderm-mini_GUI/main/installer && chmod +x installer && ./installer
```

Login Page Installation
```
wget -O installer-login https://raw.githubusercontent.com/ryanfauzi1/xderm-mini_GUI/main/installer-login && bash installer-login
```

for Manual Update
```
wget -O update-manual https://raw.githubusercontent.com/ryanfauzi1/xderm-mini_GUI/main/update-manual && chmod +x update-manual && ./update-manual
```

### Additional Installation
Theme Installation by Agus Sriawan
```
wget -O installtheme https://raw.githubusercontent.com/ryanfauzi1/xderm-mini_GUI/main/installtheme && bash installtheme
```

Fix Download xderm-mini.php
```
wget --no-check-certificate "https://raw.githubusercontent.com/helmiau/openwrt-config/main/fix-xderm-libernet-gui" -P /root/ && chmod 777 /root/fix-xderm-libernet-gui && cd /root && bash fix-xderm-libernet-gui
```

### Credits
- @ryanfauzi1
- Agus Sriawan
- @vitoharhari
- @helmiau

Thank you
