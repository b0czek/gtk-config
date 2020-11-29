# gtk-config
My personal scheme settings for gnome gtk-3.0    

In order to import, files have to be inserted in `~/.config/gtk-3.0/`, after that being done, hit `Alt`+`F2` and run `r`.  
For gnome-terminal to accept changes, following commands must be typed in:  
```bash
gsettings set org.gnome.Terminal.Legacy.Settings headerbar false  
gsettings set org.gnome.Terminal.Legacy.Settings default-show-menubar false  
setsid gnome-shell --replace  
```
After the last command, whole GNOME should crash and after relog, everything should be good to go.

