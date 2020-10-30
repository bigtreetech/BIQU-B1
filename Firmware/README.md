## Version - 2020-08-18
### Motherboard
The latest version: `Marlin 2.0.6 (Oct 30 2020 17:58:46)` --- (Compared with Aug 24 2020: quick fix - disable `MONITOR_DRIVER_STATUS` Avoid unlocking stepper motor during printing)
 * `Marlin 2.0.6 (Aug 24 2020 15:11:48)` --- (Compared with Aug 18 2020: quick fix - disable `LIN_ADVANCE` Avoid gaps layer in pause/resume printing)
 * Update Marlin version to v2.0.6
 * Add the function of saving "babystep value" to EEPROM,

### Touch Screen
The latest version: `TFT35_B1_V3.0.26.x Aug 18 2020`
 * Add more parameter settings in "Settings->Machine->Parameter" menu
 * Using [Cura plug-in](https://github.com/bigtreetech/Bigtree3DPlugin) to generate the icons needed for model preview
 * Add the option to turn off the power-loss-recovery function In the "Settings->Feature" menu, fixed the bug of the z-axis height is not correct when power-loss-recovery after printing be paused
 * Optimize the layout of the title bar temperature status display
 * Add the Rotary Knob RGB sleep option (sleep synchronously with LCD), and add 0% option to LCD sleep brightness. Now all lights of the printer can be turned off completely
 * Add Marlin firmware version and machine type display in "Settings->Info" menu
 * Optimize the pop-up dialog, Some known echo that do not need to click "confirm" will show in title bar and disappear automatically after a while
 * Add the function of saving "babystep value", the value will not disappear after home or reset
 * Add plane test menu, use with babystep menu to make bed leveling more convenient.

## Version - 2020-06-15
* The original version
