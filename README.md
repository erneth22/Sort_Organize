# Sort_Organize
Automation tool for sorting and cleanup of DJI and GoPro drone footage.
Organizes clips into date-based directories and removes videos
below a specified minimum duration.

!!! Always use --dry when running first time !!!

Prerequisites
Install system dependencies:

# Arch/CachyOS
```bash
sudo pacman -S python mediainfo
```
# Ubuntu/Debian
```bash
sudo apt install python3 mediainfo
```
# Install dependencies
```bash
pip install pymediainfo
or
sudo pacman -S python-pymediainfo
```

# Make it Executable:
```bash
chmod +x Sort_Organize
```
# copy to PATH
```bash
cp Sort_Organize ~/.local/bin/
```

# USAGE #
```bash
cd to/your/Drone/Footage
Sort_Organize                  # run normally
Sort_Organize --dry            # preview without making changes
Sort_Organize --min 30         # set minimum duration to 30 seconds
Sort_Organize --dry --min 30   # combine both
```
