
## Auto Install TeamSpeak 3 Server on Debian / Ubuntu
### To get admin key connect to server SSH & Run
```bash
nano /opt/ts3server/ServerAdmin_Privilege_Key.txt
```
### What this script does:
- Creates a new user to run the TeamSpeak 3 Server
- Downloads and installs the server
- Creates a systemd service
- Starts the server
### For Vultr Users, Create a script and paste this.
```bash
wget https://raw.githubusercontent.com/CorNCSGO/ts3-setup/master/install_ts3-server.sh
chmod a+x install_ts3-server.sh
sudo ./install_ts3-server.sh
```
### Then get admin key by connecting to server SSH & Running this
```bash
nano /opt/ts3server/ServerAdmin_Privilege_Key.txt
```
