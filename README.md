# slstatus - suckless status
slstatus is a small tool for providing system status information to other
programs over the EWMH property of the root window (used by dwm(1)) or
standard input/output. It is designed to be as efficient as possible by
only issuing the minimum of system calls required.


## Features
- Battery percentage/state/time left
- Cat (read file)
- CPU usage
- CPU frequency
- Custom shell commands
- Date and time
- Disk status (free storage, percentage, total storage and used storage)
- Available entropy
- Username/GID/UID
- Hostname
- IP address (IPv4 and IPv6)
- Kernel version
- Keyboard indicators
- Keymap
- Load average
- Network speeds (RX and TX)
- Number of files in a directory (hint: Maildir)
- Memory status (free memory, percentage, total memory and used memory)
- Swap status (free swap, percentage, total swap and used swap)
- Temperature
- Uptime
- Volume percentage
- WiFi signal percentage and ESSID


My personal slstatus I use with my DWM config. This config shows a date and time, battery level, Ram used in percentage, CPU used in percentage, total free space in /home (because OpenBSD uses multiple partitions) and current Upload/Download speeds.

No patches have been applied and non of the stock features are hard removed from the codebase so they can always be enabled easier later on if needed.

## Installation
Edit config.mk to match your local setup (Currently setup for OpenBSD)

Afterwards enter the following command to build and install slstatus (if
necessary as root):

    make clean install


## Running slstatus
See the man page for details.

