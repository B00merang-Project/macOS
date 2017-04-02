# macOS Sierra 
### Theme reproducing the clean and bright look of Apple's OS [(dark theme here)](https://github.com/B00merang-Project/macOS-Sierra-Dark)

![macOS-Sierra-OS-X](http://b00merang.weebly.com/uploads/1/6/8/1/16813022/screenshot-2016-12-20-14-07-38_2_orig.png)

### Recommended icon theme: [La Capitaine](https://github.com/keeferrourke/la-capitaine-icon-theme)

***

**Maintainer :** [Elbullazul](https://github.com/Elbullazul)

**Distributor :** [B00merang Project](https://github.com/B00merang-Project)

**License :** GPL v3

**More info :** http://b00merang.weebly.com/macos-sierra.html

### Manual installation

Extract the zip file to the themes directory i.e. `/home/USERNAME/.themes`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "macOS Sierra"
gsettings set org.gnome.desktop.wm.preferences theme "macOS Sierra"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "macOS Sierra"
xfconf-query -c xfwm4 -p /general/theme -s "macOS Sierra"
```

### Requirements

- GTK+ 3.6 or above
- Murrine and Pixmap theme engines

### Contribute

Contact us @ http://b00merang.weebly.com/contact.html
