#!/bin/bash
rm -rf ~/MacOSBigSurThemeConverter || error "Failed to first remove ~/MacOSBigSurThemeConverter folder"
git_clone https://github.com/techcoder20/MacOSBigSurThemeConverter.git || error "failed to download github repository!"
#Making install script executable
sudo chmod +x ~/MacOSBigSurThemeConverter/install.sh || error "Failed to make install script executable"
#Running Install script
~/MacOSBigSurThemeConverter/install.sh || error "Failed to run install script"
