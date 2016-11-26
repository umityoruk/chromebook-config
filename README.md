# chromebook-config

This repository contains the configuration files and scripts for Asus C301SA Chromebook running Xenial (Crouton) with i3wm.


**adjustBacklight**: controls the backlight similar to xbacklight (xbacklight not functional in this setup)

**adjustBrightness**: controls the screen brightness similar to adjustBacklight script. This sript can be used to dim screen past the lowest backlight setting.

**chrome**: Kill the duplicate chrome processes spawned by google-chrome. In this setup google-chrome sometimes fails to display due to starting multiple chrome processes. This script is a walk around solution to that. If you add the script location to the PATH, you can Use "chrome" command instead of "google-chrome" to start Google Chrome. 
