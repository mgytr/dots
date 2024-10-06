# dots
My dots for my Arch Linux install
# Installation
Install [yay](https://github.com/Jguer/yay) if you havent already  
Run  
```bash
yay -S zsh foot wofi hyprland hyprpaper gnome-control-center waybar cowsay fortune-mod fastfetch nano oh-my-zsh-git zsh-theme-powerlevel10k-git
```  
(also install gdm and start it using `sudo systemctl enable --now gdm` if you dont have a login manager)
  
Copy the contents of this folder to your home folder (except the directory cows)  
Copy the cows/miku.cow to /usr/share/cowsay/cows  
If you get asked to configure powerlevel, exit using Q  
And last, install CozetteVector from [here](https://github.com/slavfox/Cozette?tab=readme-ov-file#linux) (NOT OTB!)
