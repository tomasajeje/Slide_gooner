# Slide


Slide is a panning X window manager made by kantiankant but modified by me

> Note: This README is incomplete

---

## dependencies

- libx11

## Installation

```sh
make
doas make clean install
```
## Default binds

```
Super + Q: spawns terminal (st) 
Super + W: Kills windows
Super + Shift + E: kills Slide
Super + E: spawns yazi via kitty
Super + C: Centers the focused winow
Super + H/J/K/L: Pans the viewport in the corresponding direction (left,down, up, right) 
Super + Shift + H/J/K/L: moves the focused window in the corresponding direction (left,down, up, right)
Super + Ctrl + H/L: cycles windows in a forward/backward cycle 
```
## Configuration

All configuration is done via the config.h file and is reloaded via recompiling and logging back in. 

---

## Credits
- Based on the original work by [@kantiankant](https://github.com/kantiankant).

## License

GPL-v3

