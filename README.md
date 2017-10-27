# fix-usb-wifi-dongles-connections-problems
This code fixes USB WIFI Dongles connections problems. Sametimes the dongles could be detecting the wifi networks, perhaps can't connect on these ones. 

<b>Perform the following commands as 'root':</b>

`echo -e "[device]\nwifi.scan-rand-mac-address=0" >> /etc/NetworkManager/NetworkManager.conf`

`systemctl restart network-manager`
