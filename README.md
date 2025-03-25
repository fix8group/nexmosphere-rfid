# RFID table: reader specifications and installation

This guide is for set builders looking to integrate a Nexmosphere RFID reader into built element for exhibition use, based on the software and control systems developed by Fix8Group.

## Schematic

![Schematic](schematic2.svg)


## Parts

### XR-CR10 10-centimetre RFID antenna [[datasheet](https://static1.squarespace.com/static/6554c6b08c8bde3649fca4ed/t/66bf2cebea261169975d5e21/1723804908273/nexmosphere-xr-antenna-circular-datasheet.pdf)]

This is a circular PCB with a c. 100mm long cables on it. It needs to be mounted underneath the RFID detection zone - see below for further details.

### XR-DW2 RFID antenna driver [[datasheet](https://static1.squarespace.com/static/6554c6b08c8bde3649fca4ed/t/66bcbb4959d61339c78c0a25/1723644747148/nexmosphere-xr-dw2-rfid-driver-datasheet.pdf)]

This connected to the antenna, and so will need to be mounted close to it.

### XN-125 X-talk interface board [[datasheet](https://static1.squarespace.com/static/6554c6b08c8bde3649fca4ed/t/66bf4c3794fa39336ea51421/1723812921205/nexmosphere-xn-115_125-datasheet.pdf)]

This is connected to the XR-DW2 antenna driver with a 40cm x-talk cable and provides a USB connection for the host PC.

## Antenna placement

The antenna  is mounted to the underside of the detection zone, directly under the area where the RFID tag will be placed. This is typically on the underside of some MDF forming the top surface of the exhibit.

No metal should be placed between the antenna and the RFID tag (or within 20cm of it), as this will interfere with the signal.

## RFID tags

The RFID tags used with this system vary by applciation, but are typically 3D printed holdables or credit card-sized RFID cards. The tags are passive, and so do not require a power source.

## Installation

The antenna, driver and interface board should be mounted in the exhibit, during the build process. Do not use adhesive to mount the antenna as is tends to fail over time - screw this in using the holes provided on the PCB.

The driver and interface board should be screwed into the exhibit in a location that is accessible for maintenance, and will reach the host PC.