# Coding the BMW F Chassis Vehicles

(a work *in progress*)

![Graphic](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQ4IhZEzpOCraK_vByD8TGUfYKhZmEfe74ZjpaRwloceNOnkO9d7w)

> srsly though don't brick your car.

## Requirements

### Stack
* BMW Vehicle 
* [ENET Cable](https://www.google.com/webhp?sourceid=chrome-instant&ion=1&espv=2&es_th=1&ie=UTF-8#q=bmw%20enet%20cable)
* [E-SYS + PSDZData](http://f80.bimmerpost.com/forums/showthread.php?t=1040141)
* [E-SYS Launcher Premium](https://mega.nz/#F!PV9lxa4J!wvP4wFcYZVF84JBfc__lAw)
* Windows (native or virtual)
* You

### Understand the Codemandments.
1. Clicking the "Code Default Values" Button == ☠
2. Coding, or thinking about coding, the DME module == ☠☠
3. Putting others' intellectual property (BMW's or otherwise) in a public repo == ☠☠☠

## Desirements

### Contribute.
Share code: fork me, submit pull requests, ask to maintain the repo.

### Be friendly.
Seriously. Even when someone's being a newb.  

## List of ECUs/Modules | Functions
*This is incomplete as it's been taken from a MY2016*  
*Some functions are deduced and may be incomplete/inaccurate*

Module/ECU | Address | Function
---------- | :-----: | -------- 
AAG|[XX]|Trailer Hitch Module
ACC|[XX]|Adaptive Cruise Control
ACSM|[1]|Advanced Crash & Safety Management
AHM|[XX]|Trailer Module
AMP|[XX]|Amplifier
AMPH|[XX]|HiFi Amplifier
AMPT|[37]|Top Amplifier
ASA|[XX]|Active Steering
ASD|[3f]|Active Sound Design
ATM|[61]|??
DME2|[12]|Digital Motor Electronics [!!DANGER!!]
DSC|[29]|Dynamic Stability Control
EKPM2|[17]| Electronic Fuel Pump Control
EGS|[XX]|Automatic Transmission [non-DCT?]
EPS|[30]|Electronic Power Steering
FEM_BODY|[40]|Front Electronics Module (ZGW, FRM, CAS, and JBBF Combined)
FEM_GW|[10]|Front Electronics Module Gateway
FZD|[56]|Function Unit Roof
GHAS|[f]|??
HC2|[8]|Heading Control (Lane Change Warning)
HU_NBT2|[63]|Head Unit NBTv2 (MY2016+)
ICM|[1c]|Integrated Chassis Management
IHKA3|[78]|Integrated Automatic Heating/Air Conditioning System
KAFAS2|[5d]|Camera-based Driver Assist System [v2? MYXXXX+]
KOMBI|[60]|Instrument Cluster
LHM|[43]|LED Headlight Main Module
LHM|[44]|LED Headlight Main Module
REM|[72]|Rear Electronics Module
SM2|[6d]|Seat Module / Seat Memory
SM2|[6e]|Seat Module / Seat Memory
TBX|[35]|iDrive Controller Touch Handwriting Module
TMS|[41]|LED Headlight Secondary Module (stepper servos, marker, positioning light, indicators)
TMS|[42]|LED Headlight Secondary Module (stepper servos, marker, positioning light, indicators)
TRSVC|[6]|Surround View Camera System
VDC1|[76]|Vertical Dynamics Management
ZBE3|[67]|iDrive Controller
ZGW|[XX]|Central Gateway Module

## Helpful Resources
[bmwesys.com Guides](http://bmwesys.com/guides/) - credit to Antonio Vernacchia
