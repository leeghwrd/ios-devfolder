# iOS Development Folder

Simple bash script for use on iOS Jailbroken devices.

# Why
Provides a work-around for the `killed: 9` error received when
executing binaries from within `/var/mobile` directory.

# What it does
- Creates `/opt/development` folder in root directory
- Adds `Development` symbolic link inside of mobile's home directory
