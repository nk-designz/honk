# Honk
a bash-written small script for persistently managing your clipboard with dmenu and xclip
## Preinstallation
You need to have
* xclip
* dmenu _or rofi just ```sed -i 's/dmenu/rofi/g' honk``` befor install_
* wget  _for updates_
installed.

On Arch:
```bash
pacman -Sy xclip dmenu wget
```
## Installation
Run the script from github
```bash
wget https://raw.githubusercontent.com/nk-designz/honk/master/honk &&  \
less ./honk && \
chmod +x ./honk && \
sudo ./honk install
```
### Alternatively
Clone the Repo and run
```bash
sudo ./honk install
```
Start the watcher:
```bash
honk watch
```
## Usage
```bash
honk
```
or
```bash
honk select
```
