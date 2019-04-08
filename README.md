# Termux-Setup-Tips-For-Android
Some setup tips for Termux on Android


## Install Termux
1. Install Termux:
https://play.google.com/store/apps/details?id=com.termux&hl=en

https://termux.com/

2. Open Termux on your android device

## Setup Extra Keys
1. Create .termux/ directory
```shell
mkdir .termux/
```

2. Create termux-properties file
```shell
nano .termux/termux-properties
```

add the following string
```nanorc
extra-keys = [['ESC','/','BACKSPACE','-','|','HOME','UP','END','PGUP'],['TAB','CTRL','ALT',':',';','LEFT','DOWN','RIGHT','PGDN']]
```

and save the file by pressing "CTRL + O" or "CTRL + X"

exit and restart termux or reload settings by typing the following:
```shell
termux-reload-settings
```

This will add the following extra keys
Col 1 | Col 2
----- | -----
Content from cell 1 | Content from cell 2

## Setup Termux Access Storage
Run the following command in Termux
```shell
termux-setup-storage
```

## Install Python
```shell
pkg install python
```
or
```shell
apt install python
```
