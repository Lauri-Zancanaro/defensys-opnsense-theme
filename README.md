# defensys-opnsense-theme
[&lt;/] defensys - OPNSense - Theme

## Install Theme

- Connect via ssh to OPNSense Firewall
- Install git
- Clone Project to directory /root
- Copy defensys theme directory to /usr/local/opnsense/www/themes/
  
```
pkg install git
cd /root
git clone https://github.com/Lauri-Zancanaro/defensys-opnsense-theme.git
cp -r /root/defensys-opnsense-theme/defensys /usr/local/opnsense/www/themes/defensys
cd /usr/local/opnsense/www/themes/
ls -l
```

- In WEBUI go to System > Settings > General > Theme
- Select Defensys Theme and Save
- Force Browser to renew images (Ctrl + Shift + R)
