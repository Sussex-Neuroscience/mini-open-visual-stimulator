# mini-visual-stimulator

This is documentation for setting up a visual stimulator based on a DLPLCR230 from Texas instruments. It is a smaller LCr, with lower cost that can be controlled with an RPi.



#### LEDs:

uses Osram LEDs, specifically red (KR CSLNM1.23_EN), green (KP CSLNM1.F1_EN), and blue (KB CSLNM1.14_EN).
Useful info about them:
- Forward Voltage: ~2.7-3.2V
- Current ~2A
- ~120 lumens
- 1212 (3030 metric footprint).
- soldered to custom (but seemly simple to replicate) PCBs

For ZebraFish we need the following wavelengths:
- 365
- 420
- 470 (possibly GB CS8PM1.13-HZKZ-35-0-350-R18)
- 588

For mice:
- 385
- 590