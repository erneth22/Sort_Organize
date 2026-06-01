# Sort_Organize
Automation for  sorting and removal of DJI + GOPRO movies

Prerequisites
Install system dependencies:

# Arch/CachyOS
sudo pacman -S python mediainfo

# Ubuntu/Debian
sudo apt install python3 mediainfo

pip install pymediainfo
or
sudo pacman -S python-pymediainfo

# Make it Executable:
chmod +x Sort_Organize

# copy to PATH
cp Sort_Organize ~/.local/bin/


# USAGE #
```bash
cd to/your/Drone/Footage
Sort_Organize                  # run normally
Sort_Organize --dry            # preview without making changes
Sort_Organize --min 30         # set minimum duration to 30 seconds
Sort_Organize --dry --min 30   # combine both
```
