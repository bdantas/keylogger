# keylogger
A minimalistic keylogger for UNIX-like operating systems running X

# Requirements:
- UNIX-like operating system (GNU/Linux or BSD) running the X window system
- Required: *xinput* and *xmodmap*

# Installation:
```
$ sudo apt install xinput x11-xserver-utils
$ cd /tmp
$ wget https://github.com/bdantas/keylogger/archive/master.zip
$ unzip master.zip
$ sudo cp ./keylogger-master/keylogger /usr/local/bin/keylogger
$ sudo chmod a+x /usr/local/bin/keylogger
```
Notu: If your operating system is not Debian-like, adjust the first step

# Usage:
`$ keylogger`
