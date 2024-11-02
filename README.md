# dwm
This is my own build of dwm
### /!\ THIS IS NOT THE OFFICIAL SUCKLESS REPO /!\

# Installation
1. Clone the repo
```
git clone https://github.com/Alce-tar-gz/dwm.git
```
_i would recommend doing this in ~/.local/source/_
---
2. Go inside the repo
```
cd dwm
```
---
3. Compile it from source
```
sudo make install clean
```
---
4. **if you want to use a login manager** create /usr/share/xsessions/dwm.desktop and write this in it:
```
[Desktop Entry]
Encoding=UTF-8
Name=DWM (X11 - X.org)
Comment=Log in using the Dynamic Window Manager
Exec=/usr/local/bin/dwm
Icon=/usr/local/bin/dwm.png
TryExec=/usr/local/bin/dwm
Type=XSession

```
