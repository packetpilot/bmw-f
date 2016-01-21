# Coding the BMW F Chassis Vehicles

(a work *in progress*)

![Graphic](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQ4IhZEzpOCraK_vByD8TGUfYKhZmEfe74ZjpaRwloceNOnkO9d7w)

> srsly though don't fucking brick your car.

## Requirements

### Stack
* F-chassis BMW 
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
Seriously. Even when someone's being a newb, especially when that someone is @thisisdave.  
(But maybe be a snarky-but-friendly dick-with-a-smiley-face-emoji in other cases.)  
joking not joking

## List of ECUs/Modules | Functions
*This is incomplete as it's been taken from a MY2016*  
*Some functions are deduced and may be incomplete/inaccurate*

* ACSM [1] | Safety Management
* AMPT [37] | Audio & Amplificaiton
* ASD [3f] | Active Sound Design (provided the module's not physically disconnected)
* ATM [61]
* DME2 [12] | Engine Management [!!DANGER!!]
* DSC [29] | Dynamic Stability Control [?] & Diff
* EKPM2 [17]
* EGS [XX] | Automatic Transmission [non-///M?]
* EPS [30]
* FEM_BODY [40] | Front/Interior Lighting & Mirrors
* FEM_GW [10]
* FZD [56]
* GHAS [f]
* HC2 [8]
* HU_NBT2 [63] | iDrive System (MY2016+)
* ICM [1c]
* IHKA3 [78]
* KAFAS2 [5d] | Driver Assist Plus [v2?|MYXXXX+]
* KOMBI [60] | Combination Dash Display
* LHM [43] | LED Headlight Main Module
* LHM [44] | LED Headlight Main Module
* REM [72] | Rear Lighting Elements
* SM2 [6d] 
* SM2 [6e]
* TBX [35]
* TMS [41] | LED Headlight Secondary Module
* TMS [42] | LED Headlight Secondary Module
* TRSVC [6]
* VDC1 [76]
* ZBE3 [67]