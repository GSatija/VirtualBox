# VirtualBox

## This is to help anyone using Mac OS and wants to download VirtualBox using command line

During this download the latest version of Virtual box was 6.0.16. 

If you want to download the latest version, do the following steps:
1. Got to this link: https://www.virtualbox.org/wiki/Download_Old_Builds_6_0
2. Right Click on the OS X Host
3. Copy the link and use it code below


## Terminal Commands:
```Terminal
  cd /tmp
  curl -O https://download.virtualbox.org/virtualbox/6.0.16/VirtualBox-6.0.16-135675-OSX.dmg
  hdiutil attach VirtualBox-6.0.16-135675-OSX.dmg
  sudo installer -pkg /Volumes/VirtualBox/VirtualBox.pkg -target /Volumes/Macintosh\ HD
  rm VirtualBox-6.0.16-135675-OSX.dmg
```
