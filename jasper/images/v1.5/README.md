# Jasper Image v1.5

[Download Link](https://link.getsync.com/#f=Jasper-All-IN-ONE&sz=14E8&t=2&s=MG2GR2EHPJQIX5UMYH6WYDO4PUHO2C7UTDISYTKVJ7OXGPFCW5TQ&i=CS7L3WXHJWY6TAKCWMIMGASZWAMUPG3M6&v=2.3)


# Jasper - Image v1.5 Release Notes
Major Updates

* Installed Home-Assistant.io 
  * Config under /home/hass/.homeassistant
  * Installed in Virtual Environment
  * Installed under the "hass" user.

* Removed clutter from rc.local
  * Was causing harmless error at boot.

* Installed needed dependencies for the development branch
  * libmad0 * libmad0-dev

* Created/Enabled Service for jasper "jasper-daemon"

* Created/Disable Service for Home-Assistant.io (user needs to enable)

* Created Script to download a specified version of Jasper/Jasper-dev
  * It is located /home/pi/Jasper-RPI-Tools/installers/jasper-repo-installer.sh
  * You can pick what branch you would like to use at clone-time

* Ensure phonetisaurus pre-compiled/installed

* Removed Erroneous cron entries

* Updated the OS and all related pkgs
