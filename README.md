# zmk-config-skeletyl
Custom hand wired BastardKB Skeletyl Build config
<img width="2160" height="3840" alt="20261116_080853-COLLAGE" src="https://github.com/user-attachments/assets/a46a1c39-cd42-48d1-b717-56c2d86b9d5e" />

Parts:
- Case printed on SV08 with Translucent Red PET-G filament. 
- Single switch PCBs used: [MxLEDBitPCB](https://github.com/swanmatch/MxLEDBitPCB)
- Controllers are: nrf52840-promicro(s)
- Switches: Gateron Smoothie
- Keycaps: PBT Pudding

<img width="3072" height="4080" alt="PXL_20250915_102650115" src="https://github.com/user-attachments/assets/d04e51a9-104c-4369-ab15-e98ca1446aeb" />

If you build your own tag me on BlueSky @glitch860.bsky.social

# How to:

If you want my keymap setup you can just download the zip file that is in the master branch and flash each side.

## How to edit keymap

If you want to make changes to the keymap, add/remove features, follow this:

Fork this repo then:
- Change the branch to main
- Edit the files for keymap, etc.
- download the zip file after the action completes and flash each side.

# How to Flash

If it is a brand new controller, When you plug it into your PC is should open as a drive.

Copy/Paste the .UF2 file to the correct half of each board. 

> Once the file is copied the drive will disappear and the keyboard should be working.

IF you already flashed the controller before, need to update the firmware

### Use a pair of tweezers to bridge the GND and RST pins. OR Use the bootloader key setup in the keymap. Each half should have a dedicated bootloader button
