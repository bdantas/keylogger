# keylogger
Minimalistic keylogger for UNIX-like operating systems

# Requirements
- UNIX-like operating system (GNU/Linux or BSD) running X window system
- *xinput* and *xmodmap*

# Installation
```
$ sudo apt install xinput x11-xserver-utils
$ cd /tmp
$ wget https://github.com/bdantas/keylogger/archive/master.zip
$ unzip master.zip
$ sudo cp ./keylogger-master/keylogger /usr/local/bin/
$ sudo chmod a+x /usr/local/bin/keylogger
```
Note: If your operating system is not Debian-like, adjust the first step

# Usage
`$ keylogger`
