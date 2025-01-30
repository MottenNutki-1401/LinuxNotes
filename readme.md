## Bash terminal commands
### cd ~/Downloads




### Git Terminal commands 
### git pull origin main --rebase
- used to fetch changes from the remote repository and reapply your local commits on top of those changes, rather than merging them
### git push -u origin main --force
- overwrite the remote branch
### Ctrl +C 
- Cancel commit process

## Installing Android Studio
- cd ~/Downloads
- tar -xzvf android-studio-2024.2.2.13-linux.tar.gz
- sudo mv android-studio /opt/
- cd /opt/android-studio/bin
./studio.sh

### Native Luncher android studio 
- 1. sudo nano /usr/share/applications/android-studio.desktop
- 2. Desktop Entry
Version=1.0
Name=Android Studio
Comment=Android Studio IDE
Exec=/opt/android-studio/bin/studio %f
Icon=/opt/android-studio/bin/studio.png
Terminal=false
Type=Application
Categories=Development;IDE;
- 3. Save and close the file (CTRL + X, then Y, then Enter).
### Check adb devices
- <img src="screenshots/adbdevices.png" width="800">

