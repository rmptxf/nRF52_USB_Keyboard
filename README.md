A simple 4 Keys USB keyboard. It can also be ported easilly to other nRF52 SOCs that supports the USB peripheral.

[**Medium Tutorial**](https://medium.com/@rmptxf/build-a-4-keys-nrf52840-based-usb-keyboard-cfab67e3ea12)

### nRF5_SDK version supported :
Versions starting from **v15.3**.

### Supported Development kits : 
The nRF52840-DK (PCA10056).

### Toolchain :
**SEGGER**. 

### How to test :
1. Clone or download the repository into : ``$nRF5_SDK_Location\examples\peripheral\`` folder.
2. Do a full erase to your SOC.
2. Build and Run into your development-Kit.
3. Connect the **nRF USB** port to the PC.  
> No problem on having both USB ports connected to the same PC.
4. Use the on-board BUTTONS to test the key press.
5. Use the terminal emulator to log the buttons press/release events.

The Buttons are configured for keys **A to D**. You can change that easilly in the ``main.c`` file. I have added comments on how to do that in the same file.

