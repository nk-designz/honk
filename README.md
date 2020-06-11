# honk
a bash-written small script for persistently managing your clipboard with dmenu and xclip
# Preinstallation
You need to have
* xclip
* dmenu (or rofi just sed -i 's/dmenu/rofi/g' honk befor install)
installed.

On Arch:
```bash
pacman -Sy xclip dmenu
```
# Installation
Clone the Repo and run
```bash
sudo ./honk install
```
Start the watcher:
```bash
honk watch
```
# Usage
```bash
honk
```
or
```bash
honk select
```
