# DOOM

![DOOM](images/doom.png)

## Setup

- [YouTube](https://www.youtube.com/watch?v=9JgQfQHHhTw&ab_channel=Gabriel_): How To Compile Vanilla Doom (Linux Doom)

### DOOM1.WAD

- Doom Wiki: [DOOM1.WAD](https://doomwiki.org/wiki/DOOM1.WAD)

```bash
linuxdoom-1.10/doom1.wad
```

### Build

```bash
cd linuxdoom-1.10
mkdir linux
make
```

### Graphics

#### Install Xephyr

- Arch Wiki: [Xephyr](https://wiki.archlinux.org/title/Xephyr)

```bash
# Ubuntu
sudo apt install xserver-xephyr

# Arch
sudo pacman -S xorg-server-xephyr
```

#### Open Xephyr

```bash
Xephyr :2 -ac -screen 960x600x8
```

or run with sudo.

## Run

In `linuxdoom-1.10` directory:

```bash
DISPLAY=:2
linux/linuxxdoom -3
```

## Controls

- Doom Wiki: [Controls](https://doom.fandom.com/wiki/Controls)

