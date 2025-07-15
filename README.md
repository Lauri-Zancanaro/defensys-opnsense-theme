# defensys-opnsense-theme
[&lt;/] defensys - OPNSense - Theme

## Install Theme

- Connect via ssh to OPNSense Firewall
- Install git
- Clone Project to directory /usr/local/opnsense/www/themes/
- Erase README.md and LICENSE Files

```
pkg install git
cd /usr/local/opnsense/www/themes/
git clone https://github.com/Lauri-Zancanaro/defensys-opnsense-theme.git
rm README.md
rm LICENSE
```

- In WEBUI go to System > Settings > General > Theme
- Select Defensys Theme and Save
- Force Browser to renew images (Ctrl + Shift + R)
