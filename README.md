

sudo snap install waven-player

or

https://snapcraft.io/waven-player


<img width="1665" height="849" alt="11" src="https://github.com/user-attachments/assets/ef9d0f43-3f81-48da-a353-bf3f7a334e29" />




https://github.com/codeboxqc/waven-player/releases/tag/1%2C8



 *******************************************************


  chmod +x Waven-x86_64.AppImage
 ./Waven-x86_64.AppImage

sudo apt install ./waven_1.0.42_amd64.deb
sudo apt remove waven

sudo snap install --dangerous waven-player_1.0.79_amd64.snap
 sudo snap remove waven-player

*********************************
 
 





sudo snap refresh waven-player

sudo snap install waven-player

snap run waven-player


sudo snap install waven-player

sudo snap remove waven-player

sudo apt remove Waven


sudo snap install --dangerous build-linux/waven-player_*.snap

sudo snap connect waven-player:pipewire || true

sudo snap connect waven-player:audio-playback || true

sudo snap connect waven-player:pulseaudio || true

sudo snap connect waven-player:alsa || true

sudo snap connect waven-player:audio-playback

sudo snap connect waven-player:audio-record

sudo snap connect waven-player:removable-media








Troubleshooting: "AppImage requires FUSE to run"
If you are using a newer Linux distribution (like Ubuntu 22.04 or later) and the file refuses to open or throws a FUSE error in the terminal, your system might be missing the required FUSE library.

You can easily fix this by installing libfuse2.

For Ubuntu/Debian/Mint:

Bash
sudo apt update
sudo apt install libfuse2
For Arch Linux / Manjaro:

Bash
sudo pacman -S fuse2

