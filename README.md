# Lily58 ZMK Config
### Forked from MC Technology's zmk-config for corne - sofle - lily58
<br>

### zmk-studio (quick start)
This repository includes the necessary configuration to use zmk-studio without
the need to configure anything else. You just have to follow the steps below:
- fork this repository y flash the firmware to the keyboard with the uf2 files (see as below en normal procedure)
- connect the master (dongle or central) to the PC
- Modify the keyboard mapping on the go with [ZMK Studio
  Web](https://zmk.studio/) and enjoy the changes!

### normal procedure
1. Fork this repository (I appreciate if you follow me on [github] and [youtube])
2. Modify the keyboard mapping with [keymap-editor]. If you want to read about
   the features of this editor you can do so here: [ZMK Studio Web](https://zmk.studio/) or [keymap-editor](https://github.com/nickcoutsos/keymap-editor).
3. Save changes and commit (optional)
4. Go to actions on github and download the artifacts
   - Actions(click) -> All Workflows (click)-> Initial User Config. (here you
     scroll to the bottom and click)
   - Here is something called artifacts, click to download the file, it is a .zip
   - now go to download on your computer (or wherever you have downloads by default):
   - unzip the .zip file
   - Connect the nice!nano v2 microcontroller to the USB-C port of your computer
   - the microcontroller is recognized as a storage device
5. Flash the firmware to the keyboard with the uf2 files (drag and drop and WITH dongle)
   - xiao_corne_dongle_xiao_dongle_display.uf2 for [seeeduino_xiao_ble] as a dongle
   - nice_corne_left_peripheral.uf2 for [nice_nano_v2] as a peripheral
   - nice_corne_right.uf2 for [nice_nano_v2] as a peripheral
6. Flash the firmware to the keyboard with the uf2 files (drag and drop and WITHOUT dongle)
   - nice_corne_left.uf2 for [nice_nano_v2] as a master side
   - nice_corne_right.uf2 for [nice_nano_v2] as a peripheral
7. If you need help, you can ask in the [ZMK Discord]
8. Enjoy your new keyboard
