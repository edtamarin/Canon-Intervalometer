# DeltaShot

This is an intervalometer based on an ESP32 for remote shutter control of a DLSR camera. Currently the device is built for Canon bodies.

## Features

The Canon bodies are triggered by shorting the focus or the shutter pin tp ground. Older versions use an N3 connector whereas newer ones use a standard jack.

The DeltaShot offers a 3.5mm jack output to interface with the camera. It is possible to trigger the camera manually at all times using two pushbutton switches on the device. However, these switches can also be triggered using the onboard ESP32 controller.

The software for the ESP32 is currently in development.
