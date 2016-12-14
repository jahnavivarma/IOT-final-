# IOT-final-project
photon wifi strength meter

A device made with a bar graph and a Particle Photon to show the WiFi strength.

Resources:
1. docs.particle.io
2. https://www.electronicspoint.com/threads/digital-walking-cane.277512/#post-1682225
3. hacterstack.io

Things used in project
Hardware components:
1. breadboard
2. particle photon
3. Led bargraph
4. connecting wires
5. 330 ohm resistors

Software apps and online services
1. Particle build ide
2. Particle app ios
3. terminal

Installation:
i have written code online on particle ide. there is no need to install any software to run the code as you can do it online. you may have to install phone apps for setting up the particle photon for first time. its available both in ios and android. or you can also set up using the terminal through your desktop. follow the instructions here https://docs.particle.io/guide/getting-started/intro/photon/.

you can follow the connections for the device from the fritzing diagram

The code takes the -127 to -1 decibel strength scale from WiFi.RSSI(), and using a simple linear ratio conversion it changes it to a scale of 0 to 10 for the 10 bars on my graph.
