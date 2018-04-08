# vm-i3wm-config4

vmware, virtualbox's i3wm configuation, especially for high resolution displays

# copy the config file to i3 config directory (backup your own if nessary)

    cp ~/.config/i3/config ~/.config/i3/config.bak
    cp config ~/.config/i3/

# change your ppi, change 118 to whatever you need

    echo "Xft.dpi: 118" >> ~/.Xresources



# put this at the end of your lightdm configuration file

    [SeatDefaults]
    autologin-user= {{your username}}
    autologin-user-timeout=0
    user-session=i3
