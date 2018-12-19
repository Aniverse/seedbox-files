## uTorrent

Download from  
http://www.oldversion.com/windows/utorrent  
http://www.utorrent.com/intl/en/downloads/linux  
https://forum.utorrent.com/topic/49588-µtorrent-webui  

### uTorrent Sever

https://forum.utorrent.com/topic/103706-how-to-install-setup-%CE%BCtorrent-utorrent-server-in-ubuntu-1604/

```
wget -q 
tar zxf utorrent-server-alpha-v3_3.tar.gz
apt-get install -y libssl1.0.0 libssl-dev

utserver -settingspath /opt/utorrent-server-alpha-v3_3/ &
```
