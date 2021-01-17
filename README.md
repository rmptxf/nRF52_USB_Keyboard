A simple 4 Keys USB keyboard.

[**Medium Tutorial**](https://medium.com/@rmptxf/build-a-4-keys-nrf52840-based-usb-keyboard-cfab67e3ea12)

### nRF5_SDK version supported :
**v15.3** and **v16.0.0**. For **17.2.0** you'll need to perform some updates, or you can just update the ``main.c`` and the ``sdk_config.h`` files on the usb composite peripheral exmaple in the v17.2.0 sdk.

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

