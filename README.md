# dot1x1 Gnome cursor theme

NOTE: NO LONGER MAINTAINED AS OF 2021-08-01

1x1 black dot cursor theme for Gnome to make all cursors 1x1 black dot (to effectively hide them)

## How to install

```
sudo pkill -9 X
git clone https://github.com/etheling/dot1x1-gnome-cursor-theme
sudo tar zxf dot1x1-gnome-cursor-theme/dot1x1-cursor-theme.tar.gz -C /usr/share/icons
sudo cp /usr/share/icons/default/index.theme /usr/share/icons/default/index.theme.orig
sudo cp dot1x1-gnome-cursor-theme/index.theme /usr/share/icons/default/index.theme
startx 
```

