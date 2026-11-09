# Customized-Lubuntu

Desktop dotfiles for Lubuntu/LXQt: kitty terminal, picom compositor, and an animated video wallpaper (xwinwrap + mplayer).

## Install
```sh
sudo apt install kitty picom xwinwrap mplayer
cp -r .config/* ~/.config/
chmod +x ~/.config/autostart/start-wallpaper.sh
```
Set your wallpaper video with `WALLPAPER_VIDEO=/path/to/video.mp4`; the default is `~/Pictures/wallpaper.mp4`. Log out and back in.
