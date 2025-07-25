# How to Use
First, you must download the dependencies
```sh
doas pacman -S xorg-setxkbmap libx11
```
Second, you must configure your "compose" key. Note that some Windows Managers, such as i3, require you to always configure this command (xinitrc). Example "RIGHT CONTROL":
```sh
setxkbmap -option compose:rctrl
```
Third, rename file for "~/.XCompose" and restart Xorg WM (reboot or relogin) and then press the chosen compose key + C (for cuneiform) + name. Example "lugal (𒈗)":
`R-Ctrl + c + lugal` or Emacs-lovers `RC c-lugal`
- (note that I left space in Emacs, because in fact, the compose key only needs to be pressed and released, not held down)
