# DART-6UL bare metal SDP loader

## Description
Adopted the imx_loader to the DART-6UL board.

## Usage

1. Force the SDP mode for the board :

-  J13.6 -> J5.8
-  J13.8 -> J5.9

2. Connect the USB cable to the OTG port (upper one)

3. Connect the micro-USB cable for the serial terminal

4. Press Reset

5. Issue ./imx_usb

6. User LED will be on, and serial tty echo mode will be enabled

