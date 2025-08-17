# Half-Wavelength Dipole for 80m in NVIS Configuration

<p align="center">
<img src="./img/internals_complete.jpg" width="400" height="500"/>
</p>

## Introduction
This article summarizes my experiences with building 80m half-wave dipol in NVIS setup.
The main goal of this project was to evaluate how practical is to install dipol antenna as low as 1m above the ground. 
I wanted to test in particular:
    - quality of regional coverage (my goal was to test connectivity in the range of 0 to 500km)
    - ease of tunning such anntenna setup

## Design
To build the anntenna I used 4mm2 insulated wire (Lgy4). Rough estimation of dimensions can be found using below formula:

To be on the safe side I used 2 x 39m wires, those dimentions produced SWR minimum slightly below 3.5MHz. Duirng antenna tunning both radiating elements were reduced (length of both radiating elements was reduced by the same amount until SWR lowest point moved to desired frequency - in my case I have chosen 3.7MHz to optimize the setup for phone communication).

$L_{\text{antenna total length}} = K \cdot \frac{c}{2f}$



## References
[1] Understanding NVIS - Rhode-Schwarz
[2] The NVIS— A Low Antenna for Regional  Communications - Albert L. Pion, KK7XO, QST June 2002
[3] A Look at NVIS Techniques - Ed Farmer, AA6ZM - QST January 1995