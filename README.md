## macOS Sierra theme reproducing the clean and bright look of OS X and macOS ##

![macOS-Sierra-OS-X](http://b00merang.weebly.com/uploads/1/6/8/1/16813022/1279540_orig.png)
More info on http://b00merang.weebly.com/macos-sierra.html

###Manual installation###

Extract the zip file to the themes directory i.e. `/home/USERNAME/.themes`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "macOS Sierra"
gsettings set org.gnome.desktop.wm.preferences theme "macOS Sierra"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "macOS Sierra"
```

### Requirements ###

- GTK+ 3.6 or above
- Murrine and Pixmap theme engines

### Code and license ###

License: GPL-3.0+

Report bugs or contribute at http://b00merang.weebly.com/contact.html
