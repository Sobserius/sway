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
gsettings set org.cinnamon.desktop.default-applications.terminal exec kitty
gsettings set org.gnome.desktop.interface color-scheme 'prefer-dark'
gsettings set org.gnome.desktop.interface gtk-theme 'Adwaita-dark'
```
wallpaper: 
```https://d1nn9x4fgzyvn4.cloudfront.net/styles/860x645/s3/2021-01/SC196248.4x3.jpg```

the rice itself: 
https://media.discordapp.net/attachments/906439569312985108/1482350466934505575/image.png?ex=69b6a1f4&is=69b55074&hm=7aa91d33af7f5b18aa15233c6ec76f5a4745427382211b945bb40a1c7b75846f&=&format=webp&quality=lossless&width=1545&height=966

https://media.discordapp.net/attachments/906439569312985108/1482351639397666856/image.png?ex=69b6a30b&is=69b5518b&hm=06074e76c9f9a0c68b5d06801f20cfa29c7c2e4ae3660f319d118758a395b0e2&=&format=webp&quality=lossless&width=1545&height=966
