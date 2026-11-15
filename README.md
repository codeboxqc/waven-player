

sudo snap install waven-player

or

https://snapcraft.io/waven-player


<img width="1665" height="849" alt="11" src="https://github.com/user-attachments/assets/ef9d0f43-3f81-48da-a353-bf3f7a334e29" />






sudo apt install ./waven-1.0.0-Linux.deb 

 



Bash
cd ~/Downloads
Make the file executable by running this command:

Bash
chmod +x Waven-x86_64.AppImage
Run the application by typing:

Bash
./Waven-x86_64.AppImage
 






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

