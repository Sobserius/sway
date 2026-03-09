```console
gsettings set org.gnome.desktop.wm.preferences button-layout ':close'
sudo pacman -S nemo nemo-fileroller sway mako fuzzel waybar swaybg

git clone https://github.com/Sobserius/sway.git ~/sway
ln -sf ~/sway/sway/config ~/.config/sway/config
ln -sf ~/sway/waybar/config ~/.config/waybar/config
ln -sf ~/sway/waybar/style.css ~/.config/waybar/style.css
ln -sf ~/sway/mako/config ~/.config/mako/config
ln -sf ~/sway/fuzzel/fuzzel.ini ~/.config/fuzzel/fuzzel.ini
```
