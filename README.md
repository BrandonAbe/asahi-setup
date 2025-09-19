# asahi-setup
My setup files for installing Asahi Linux

# Install Steps
1. curl https://alx.sh | sh
2. sudo dnf update
3. sudo dnf install git libva libdrm pyton3-pip
4. git clone https://github.com/JaKooLit/Fedora-Hyprland.git
5. cd Fedora-Hyprland/
6. chmod +x install.sh
7. ./install.sh
8. Type "y" to proceed with Hyprland install
9. Choose "n" for NVIDIA GPU
10. Select "y" for Install GTK themes
11. Select "y" for configure Bluetooth
12. Select "y" to install Thunar file manager
13. Select "n" on Asus ROG Laptop prompt
14. If using GNOME select "n" for installing SDDM, if using KDE Plasma select "y"
15. Select "n" for install of XDG-DESKTOP-PORTAL-HYPRLAND
16. Select "y" on install zsh prompt
17. Select "y" on nwg-look install
18. Select "y" on copy Hyprland dotfiles

# Python Configuration
1. curl -LsSf https://astral.sh/uv/install.sh | sh
2. export PATH="$HOME/.local/bin:$PATH"
3. uv --version

# Boot.dev setup
1. curl -sS https://webi.sh/golang | sh
2. echo 'export PATH=$PATH:$HOME/.local/opt/go/bin' >> ~/.bashrc
3. source ~/.bashrc
4. go install github.com/bootdotdev/bootdev@latest
5. bootdev --version
