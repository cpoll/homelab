# Tasks:

## Turning off monitor regularly
- turn off at startup without login
- turn off periodically

try GRUB_CMDLINE_LINUX_DEFAULT="consoleblank=60" in /etc/default/grub (do sudo update-grub after)

This seemed to work. Throw it into ansible


## Default ssh user to bash

## Set up local user and password
