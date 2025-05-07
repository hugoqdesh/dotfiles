<div align="center">

# **PYWAL DOTS**

![image](image.png)

</div>

## **Install Needed Packages**

`sudo pacman -S nano timeshift git zsh kitty nautilus ufw gnome-font-viewer ly hyprland rofi mako hyprpaper hypridle hyprlock python-pywal`

## **Enable Login Manager**

`sudo systemctl enable ly.service`

## **Install yay**

`sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si`

## **Switch To zsh**

`chsh -s $(which zsh)`

## **Install oh-my-zsh and p10k**

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

`git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`

`echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc`

## **Install Nvidia Drivers**

`sudo pacman -S nvidia nvidia-utils nvidia-settings`

## **Setup Font**

Install [Cousine Nerd Font](https://www.nerdfonts.com/font-downloads)

## **GTK Theme**

`yay -S dracula-gtk-theme`

## **Rice**

hyprland, hypridle, hyprpaper, hyprlock, kitty, zsh, waybar, mako, rofi

## **For Screen Recording**

`yay -S xdg-desktop-portal-hyprland-git`

## **Install Apps**

| Type           |
| -------------- |
| Librewolf      |
| VSCodium       |
| Brave          |
| Intellij       |
| KeePassXC      |
| Obsidian       |
| Portmaster     |
| GitHub Desktop |
| OBS Studio     |
| Kdenlive       |

## **Setup ufw**

`sudo ufw limit 22/tcp`

`sudo ufw allow 80/tcp`

`sudo ufw limit 443/tcp`

`sudo ufw default deny incoming`

`sudo ufw default allow outgoing`

`sudo systemctl enable ufw.service`

## **TODO**

- improve dots
