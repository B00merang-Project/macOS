# macOS High Sierra 
### Theme reproducing the clean and bright look of Apple's OS [(dark theme here)](https://github.com/B00merang-Project/macOS-High-Sierra-Dark)

![macOS-High Sierra](https://b00merang.weebly.com/uploads/1/6/8/1/16813022/macos-high-sierra-2_orig.png)

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
gsettings set org.gnome.desktop.interface gtk-theme "macOS High Sierra"
gsettings set org.gnome.desktop.wm.preferences theme "macOS High Sierra"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "macOS High Sierra"
xfconf-query -c xfwm4 -p /general/theme -s "macOS High Sierra"
```

### Requirements

- GTK+ 3.18 or above
- Murrine and Pixmap theme engines (usually present in the `gtk-engines` package)

### Contribute

Contact us @ http://b00merang.weebly.com/contact.html
