# IKEA STYRBAR WLED Control
Flow to use the IKEA STYRBAR Zigbee Remote to control WLED functions

![Flow image](https://github.com/nvschilleman/nodered-styrbar_wled/blob/main/flow.jpg?raw=true)

## Features:
-   ON|OFF toggle
-   Brightness UP|DOWN
-   WLED Preset PREVIOUS|NEXT
-   Random WLED Effect
-   Save state as preset

## Settings
<h4>Dimmer settings</h4>
Step increment brightness by X
<h4>WLED Presets</h4>
Number of WLED presets in your WLED setup, increments when using the Save state as preset button.


**Its important to set this value before using this flow, if you don't do this the PREVIOUS|NEXT buttons won't work and Save state as preset might overwrite one of your saved presets**


This flow is based on [this project](https://notenoughtech.com/featured/ikea-tradfri-wireless-dimmer-in-nodered/)
