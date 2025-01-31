# long_range_keyboard
Creating a wireless keyboard with a range of 10km.

\*\*\* Not yet finished\*\*\*

The goal is to create a module which can be used for two purposes. One module can be connected over USB to a keyboard which will provide input to an STM32. The other circuit will be connected to a computer (in this case an Nvidia Jetson Nano) over usb. The STM32 on the second board will emulate an HID keyboard, and will relay the keystrokes from the keyboard which will be sent between the devices over LORA wireless communication. The board is in the PCB layout stage.
