
 **st - the simple (suckless) terminal**
 
## Installation for newbs

You should have xlib header files and libharfbuzz build files installed.

```
git clone https://github.com/LukeSmithxyz/st
cd st
sudo make install
```
## Dependencies

```
# Void
xbps-install libXft-devel libX11-devel harfbuzz-devel libXext-devel libXrender-devel libXinerama-devel

# Debian (and ubuntu probably)
apt install build-essential libxft-dev libharfbuzz-dev

# Nix
nix develop github:siduck/st

(most of these are already installed on Arch based distros)

# Install font-symbola and libXft-bgra
```

## Try it out!
