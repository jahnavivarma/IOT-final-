Internet of Things final project

WiFi strength meter
A device made with a bar graph and a Particle Photon to show the WiFi strength.

Resources:
•	Docs.particle.io
•	https://www.electronicspoint.com/threads/digital-walking-cane.277512/

THINGS USED IN THIS PROJECT
Hardware components
•	breadboard
•	particle photon
•	jump wires
•	resistors
•	bargraph LED

Software apps and online service:
•	particle build ide
•	particle app ios
•	terminal

Installations:
I have coded online using particle ide. There is no need to install any software since the ide is online. You might be needing to install the particle for initial setup of the photon. The app is available in both android and ios. You can also install using desktop terminal. You can follow the steps here for setting the photon https://docs.particle.io/guide/getting-started/start/photon/.

The code takes the -127 to -1 decibel strength scale from WiFi.RSSI(), and using a simple linear ratio conversion it changes it to a scale of 0 to 10 for the 10 bars on my graph.

Flash to your Photon he code from build.particle.io after verifying it.

You can follow the connections by referring to the fritz diagram attached.

