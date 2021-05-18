# Shell

## GNome

```bash
dconf-editor
```

```bash
gsettings set org.gnome.shell.extensions.desktop-icons show-home false
gsettings set org.gnome.shell.extensions.desktop-icons show-trash false
```

## HTTP Server

Local IP address:
```
# MacOS
ipconfig getifaddr en0

# Linux
hostname -I
```

Public IP Address:
```
# MacOS + Linux
curl ifconfig.me
```

Firewall:
```
sudo ufw allow from any to any port 8000 proto tcp
sudo ufw allow from any to any port 8000 proto udp

sudo ufw status

sudo ufw deny from any to any port 8000 proto udp
```

## References
* https://askubuntu.com/questions/1230877/how-to-remove-home-folder-icon-from-desktop-in-ubuntu-20-04
