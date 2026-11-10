# bullet-microphone

A microphone to use outdoors for a BirdNET station, built around the [PUI Audio AOM-5024 electret capsule](./AOM-5024L-HD-F-R.pdf). 

The housing is a 3D-printed bullet with the capsule pressed into the nose, and a small preamp board inside the body.

The capsule is designed to be easily replaceable if it fails due to weather exposure.
The threaded connection and cable strain relief are waterproofed by covering with glue-filled heatshrink tubing.

It seems to work well. It has been exposed for a year to the elements and still sounds just fine. It is a lot more sensitive than I expected.

<a href="images/mic.jpg"><img src="images/mic.jpg" alt="Finished bullet mic" width="600"></a>

<a href="images/birdnet-go.png"><img src="images/birdnet-go.png" alt="BirdNET-Go daily activity" width="480"></a>

## Pre-Amp Circuit

The preamp is a discrete circuit powered by phantom power, based on [ESP Project 93](https://sound-au.com/project93.htm):

| Pin (J2) | XLR |
|---|---|
| 1 | Ground |
| 2 | Hot (signal + phantom) |
| 3 | Cold (phantom, AC-grounded) |

## PCB

The PCB is designed to be inserted into a T-shaped slot in the housing. When selecting the capacitors,
height was a consideration.

<a href="pcb/Electret%20Mic%20Preamp%20v1.1%20Top.png"><img src="pcb/Electret%20Mic%20Preamp%20v1.1%20Top.png" alt="PCB top" width="600"></a>

<a href="pcb/Electret%20Mic%20Preamp%20v1.1%20Bottom.png"><img src="pcb/Electret%20Mic%20Preamp%20v1.1%20Bottom.png" alt="PCB bottom" width="600"></a>

## Case

<a href="images/case-1.png"><img src="images/case-1.png" alt="Cap 1" width="360"></a>
<a href="images/case-2.png"><img src="images/case-2.png" alt="Cap 2" width="315"></a>

<a href="images/case-3.png"><img src="images/case-3.png" alt="Body 1" width="440"></a>
<a href="images/case-4.png"><img src="images/case-4.png" alt="Body 2" width="360"></a>

## Notes For Next Revision
- Space the electrolytic caps out a little more. They currently *just* touch, and lean slightly. Or select different capacitors.
- Label the I/O pins on both sides if there is room.

## Build

<a href="images/housing-front.jpg"><img src="images/housing-front.jpg" alt="Housing nose with capsule bore, and cap" width="360"></a>
<a href="images/housing-rear.jpg"><img src="images/housing-rear.jpg" alt="T-shaped board slot and threaded joint" width="360"></a>

<a href="images/pcb-assembled-top.jpg"><img src="images/pcb-assembled-top.jpg" alt="Assembled preamp, capacitor side" width="360"></a>
<a href="images/pcb-assembled-bottom.jpg"><img src="images/pcb-assembled-bottom.jpg" alt="Assembled preamp, SMD side" width="360"></a>
