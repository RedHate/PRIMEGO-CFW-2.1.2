![Screenshot](https://raw.githubusercontent.com/RedHate/Prime-GO/main/splash.jpg)


# Denon Prime GO - Custom Firmware

## What's different than a stock firmware?
- Has ssh with sftp enabled.
- Has a lighttpd server for downloading files from the unit.
- Has a custom boot splash.
- Root password set to nothing.

## How to install:
  1) Download all the parts then extract the image named PRIMEGO-2.1.2-Update.img
  2) Copy the image to the root of an SD or USB card then install from the settings menu.

## How to ssh in:
  1) Get the IP address of the Mixstream Pro from the wifi menu
  2) On Linux: Open a terminal and type ssh ipaddresshere. On windows try using putty, the ssh port is 22.
  
## How to view the http server:
  1) Enable wifi and connect to a network
  2) Open the wifi settings menu and click the ap you are connected to and get the ip address.
  3) Open a browser on your computer and type http://IPADDRESSHERE
