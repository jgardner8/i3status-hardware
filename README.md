# i3status-hardware
A lightweight shell script that augments i3status information with hardware info such as cpu/ram/disk usage, wifi ssid/strength, ip address, battery information etc.

## Features
- Colours information based on importance. Colours are by default set as shades of grey, based on importance. Lighter shades (important info) show more strongly against the black background of i3bar, whereas dark shades (unimportant info) are almost hidden.
- Importance is based on figures retrieved, not category. E.g. RAM usage: 13% is not important, whereas RAM usage: 95% is very important.
- Displays: Dropbox status, CPU Usage, RAM Usage, Disk Usage, Current bandwidth usage, Battery info, Wifi ssid/strength, IP address
- This project is a good example of how to retrieve this information, as it doesn't require many dependencies; the information is taken either from the file system (/proc or /sys) or basic utilities such as free.

## Dependencies
- i3status/i3bar
- Optional: dropbox for dropbox status
- Optional: iw for wifi info
