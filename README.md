# NSPanel_V2
 Custom Firmware for the Sonoff NSpanel (EU) version.
 CREDIT & THANKS TO THE FOLLOWING.
 * Initial work: Masto github: https://github.com/masto/NSPanel-Demo-Files
 * Fully custom firmware: Marcfager github: https://github.com/marcfager/nspanel-mf

# NOTES:
* Everything is configurable from within the esphome yaml and most things have been brought out into substitutions at the top, only the button names have to be edited towards the end of the file. I couldn' do macfagers approach because I really have pushed the size limit of the yaml with this. We are restricted on the size of the yaml so i've had to use a few basic ways of doing some things, like hard coding the button names etc, but at least they are all edited within the esphome yaml. so no need to edit the HMI/tft files.

# Features:

## General:
* Touch-screen offset calibrated.
* Auto Upload .HMI file when new one is compiled in the Nextion editor.
* Auto Home.
* Auto Dim.
* Auto Screen-saver (I control this with automations in HA).
* Swipe between pages.
* Buzzer (tune after boot).
* Notifications on Home Page.


##### Pysical Switches:
* Switch 1 turns on/off Heating.
* Switch 2 turns on/off Hot water.

# Pages:

## ScreenSaver Page:
* Current Time and date dark on dark.
* Status bar icons hot water and heating dark on dark.
* Heating status Bar Icon dark on dark.
* Hot water status Bar Icon dark on dark.


## Home Page:
* Current weather symbols with transparent backgrounds.
* Feels like Temp (needs HA addon from Hacs repos).
* Time (from HA).
* Date (from HA).
* Notifications, auto home when recieved and buzzer tune.
* Temperature from internal sensor.
* Target temperature (for HA climate component).
* Hot water Temperature.
* Target temperature up button.
* Target temperature down button.
* Arched Slider for target temperature.
* Hot water temperature in the status bar.
* Hot water status bar Icon.
* Heating status Bar Icon.
* Blue line above physical switches as a state flag.

## Lights Page:
* 6 Light switches(with state changing icons and transparent backgrounds).
* 1 dimmer slider (controls 3 of the lights, select which light dims by long pressing whichever light).
* Hot water temperature in the status bar.
* Hot water status bar Icon.
* Heating status Bar Icon.
* Light dimming option status bar icon.
* Blue line above physical switches as a state flag.

## Music Page:
* 6 Radio station buttons (station url's setup in HA).
* Now playing song title & artist (this doesn't work when calling the url's to my google home mini, but does when I say "hey google, play smoothfm" for example.
* Play/Pause button (controls media player).
* Volume up button (controls media player).
* Volume down button (controls media player).
* Hot water temperature in the status bar.
* Hot water status bar Icon.
* Heating status Bar Icon.
* Blue line above physical switches as a state flag.

## Screen shots:
coming soon...

## Video Link:
coming soon...

# Extra Info:
coming soon...
