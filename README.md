![Graw DFM-17 Programming Breakout Clip](/images/balloon%20jockey.png)

# Graw DFM-17 Programming Breakout Clip (Balloon Jockey)

## Preface
A radiosonde is the active data collecting payload of a weather balloon, recording temperature, pressure and its own GNSS tracked position and transmitting this to receivers on the ground. In many states, these balloons and their radiosondes are launched two times a day by the United States National Weather Service to help improve weather forecasting models. They often fly up to 35 Kilometers, their balloons popping near the edge of the atmosphere, at which point they float down with the assistance of a parachute. They can then be collected and kept, as the NWS does not request that these devices be returned, only disposed of responsibly (this information is printed on every radiosonde launched). 

The Graw DFM-17 is one of the most commonly launched model of radiosonde in the US. Unlike the Viasala RS41 (another common 'sonde), the programming interface of the DFM-17 is difficult to utilize. Both these devices use a STM32 based microcontroller to execute the data collection and transmission logic, and both are programmable via a Single Wire Debug (SWD) port, but the DFM-17 lacks pins or a hardware connector to interface with, instead only having unpopulated fine pitch solder pads. These pads are delicate, and require a steady hand and keen eye to solder wires onto.

## Purpose
This project was created to ease functional re-use of GRAW DFM-17 Radiosondes by providing an easily attachable SWD port breakout, providing clear labeling and allowing one to use Dupont style cables to connect an ST-Link Programmer.

[RS41ng](https://github.com/mikaelnousiainen/RS41ng) is a popular and sucessful project aimed at creating alternate firmwares for radiosondes, including the Graw DFM-17.
