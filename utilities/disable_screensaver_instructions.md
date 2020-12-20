# STICKY: Howto: Disable Screen Saver In Raspbian

* [raspberrypi.org/forums link](https://www.raspberrypi.org/forums/viewtopic.php?t=57552)



Additional info [archlinux.org](https://wiki.archlinux.org/index.php/Display_Power_Management_Signaling)
Add these lines to `/etc/xdg/lxsession/LXDE/autostart`
```
@xset s noblank
@xset s off
@xset -
```