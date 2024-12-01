# Home Assistant Blueprints

Repository containing custom automation blueprints and other helper files for living well with Home Assistant and its devices.

# Automations

Automations are placed in the [automations](automations) directory.

## Color + Temp Light Alarm

I failed to find a proper light alarm for the light bulb I bought due to its unusual behavior.
It is pretty bright on lowest setting in white mode and even darker on brightest setting in color mode.
Due to this fact, using only white mode is not sufficient for a wake up light alarm and this automations is supposed to leverage both modes in order to achieve smooth transition from very dark warm to very bright cold light.

This has been created for TUYA TS0505B Smart RGB Light Bulb.
