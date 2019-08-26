# Autores
Automatic 1920 x 1080 resolution hot fix for Ubuntu and Lubuntu

This is a quick fix for a bug I encountered on my Ubuntu and Lubuntu virtual machines. For some reason the display settings did not allow me to use my native 1920 x 1080 resolution, but offered other options instead. Hopefully this helps you out if you run into the same bugs!

## Installation
Download the autores.sh and autores.desktop files. Place the autores.sh file in the user directory or wherever you see fit and update the .desktop file accordingly. Ensure you've updated the .desktop file to reflect the same. Ensure the autores.sh file is executable by running chmod -x autores.sh 

Open your file explorer in root mode and copy the .desktop files to /usr/share/applications and /etc/xdg/autostart/

Reboot and if all goes well your resolution should change to 1920 x 1080 automatically. You can edit the autores.sh file to adjust it to something else.
