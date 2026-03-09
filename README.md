```console
gsettings set org.gnome.desktop.wm.preferences button-layout ':close'
sudo pacman -S nemo nemo-fileroller sway mako fuzzel waybar swaybg swayidle swaylock xdg-desktop-portal-wlr polkit-gnome accountsservice grim slurp wl-clipboard

git clone https://github.com/Sobserius/sway.git ~/sway
ln -sf ~/sway/sway/config ~/.config/sway/config
ln -sf ~/sway/waybar/config ~/.config/waybar/config
ln -sf ~/sway/waybar/style.css ~/.config/waybar/style.css
ln -sf ~/sway/mako/config ~/.config/mako/config
ln -sf ~/sway/fuzzel/fuzzel.ini ~/.config/fuzzel/fuzzel.ini
```
Remove KDE: 
```console
sudo pacman -R konsole dolphin plasma-desktop
sudo pacman -R libkscreen kmenuedit kglobalacceld kdecoration kde-cli-tools knighttime kpipewire kscreenlocker ksystemstats kwayland kwin plasma-workspace-wallpapers plasma5support polkit-kde-agent xdg-desktop-portal-kde powerdevil plasma-workspace breeze aurorae plasma-pa plasma-integration
```
Optional:
```console
sudo pacman -Rns $(pacman -Qtdq)
```
