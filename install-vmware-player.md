#here are scripts to easily install VMWare Player on a Debian based Linux distro.
```
sudo apt install build-essential -y
```
```
sudo apt install build-essential linux-headers-generic -y
```
```
wget --user-agent="Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0" https://www.vmware.com/go/getplayer-linux
```
```
sudo chmod +x getplayer-linux
```
```
sudo ./getplayer-linux --required —eulas-agreed
```
Uninstall:
```
sudo /usr/bin/vmware-installer -u vmware-player
```
