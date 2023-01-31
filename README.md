wipi-bridge-ui
==============

This is the corresponding node-red based  user interface for the wipi-bridge

### About

WI-PI Bridge is a Raspberry PI(RPi) based Wi-Fi Bridge for routing clients to internet connection through a router, often used as a repeater, or bypass enterprise wpa security protocol.

### Installation
- The RPi OS image file can be downloaded [here](https://drive.google.com/file/d/1kfivoJRY1-tfTbqO5MyLWXaK64weQToH/view?usp=share_link).
- You can install the image file onto a microSD card using the [RPi Imager application](https://www.raspberrypi.com/software/).
- Once the image file has been copied to the microSD card, instert the card into the RPi, plug in the wifi-dongle into the USB port of the RPi, and then boot the device.
- Done, the WI-PI bridge should be working! Check your network wifi connections for the SSID [wipi_bridge]

### Connecting to the WI-PI bridge dashboard
User Access: Web-browser​

#### Accessing through connected network connection
Address: [](wipi-bridge.local:1880/) (mdns) or[](x.x.x.x:1880/)(x.x.x.x is the network IP of the WI-PI Brigdge assigned by the router)​

#### Access without network connection(First time Connecting):​

- Connect client to Access Point (default: wipi_bridge, psk: adamchuk)​

- On web browser go to: [](10.0.1.1:1880/​)

- Configure settings



