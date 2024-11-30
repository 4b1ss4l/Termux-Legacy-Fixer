# Termux-Offline-BootsTrap-Fixer
```ShellSession
cd ../usr/etc/apt/
```
```ShellSession
echo "deb https://packages.termux.dev/termux-main-21/ stable main" > sources.list
```
```ShellSession
cd sources.list.d
```
```ShellSession
echo "deb https://termux.dev/game-packages-21-bin games stable" > game.list
```
```ShellSession
echo "deb https://termux.dev/science-packages-21-bin science stable" > science.list
```
```ShellSession
cd ~
```
```ShellSession
apt upgrade -y &&
```
Y
N
Y
