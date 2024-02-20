## Install Postman On Elementary OS

> [!tip] Download postman linux file tar.gz from [here](https://www.postman.com/downloads/)
> 

> [!tip] Unzip and move to opt 
```shell
tar -xzf Postman-linux-x64-7.32.0.tar.gz
sudo mkdir -p /opt/apps/
sudo mv Postman /opt/apps/
sudo ln -s /opt/apps/Postman/Postman /usr/local/bin/postman
postman
```

> [!tip] Create a desktop shortcut
```shell
# Run
sudo nano /usr/share/applications/postman.desktop
# Paste this code
[Desktop Entry]
Type=Application
Name=Postman
Icon=/opt/apps/Postman/app/resources/app/assets/icon.png
Exec="/opt/apps/Postman/Postman"
Comment=Postman Desktop App
Categories=Development;Code;
```

## Remove postman from Linux

```shell
sudo rm -rf /opt/apps/Postman && rm /usr/local/bin/postman
sudo rm /usr/share/applications/postman.desktop
```