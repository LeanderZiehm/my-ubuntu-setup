Open Home Filenamager	Super (Windows Key) + E	Opens the file explorer (Nautilus on GNOME).



l for ls -l



# Setup 

```
bash install.sh
```




# Unistall

```
bash uninstall.sh
```



## see all available shortcuts and set values:

```
gsettings list-recursively org.gnome.settings-daemon.plugins.media-keys
```


# Other

chmod +x /home/user/Nextcloud/PATH/utils/yt.py

sudo ln -s /home/user/Nextcloud/PATH/utils/yt.py /usr/local/bin/yt

sudo rm /usr/local/bin/yt




#

nano ~/bin/g
#!/bin/bash
git add . && git commit -m "+" && git push
chmod +x ~/bin/g
export PATH="$HOME/bin:$PATH"
source ~/.bashrc  # or source ~/.zshrc
