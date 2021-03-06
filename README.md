# FlameNightlyUpdaterTool

![Screenshot](Screenshot.png)

This script provides a Tool that automates the Update process for the [Alcatel One Touch Flame](https://developer.mozilla.org/it/Firefox_OS/Developer_phone_guide/Flame) to lastest Nightly.   

It will download Gaia and b2g from [official Mozilla server](http://ftp.mozilla.org/pub/mozilla.org/b2g/nightly/latest-mozilla-central-flame-kk/), extract them and then flash it on the phone using ADB.   
The script also allow you to take a backup of your current b2g in order to recover the phone.   

Features
=======

- update both Gaia and Gecko
- update Gonk from the base image
- backup your data
- restore your data (you will be logged out of most apps)
- add the UDEV rule for the Flame reference device
- switch to `nightly-test` FOTA channel

N.B. in order to use this script you have to install ADB on your Linux distribution (for Debian/Ubuntu the package is `android-tools-adb`).   
