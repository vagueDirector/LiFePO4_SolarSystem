# LiFePO4_SolarSystem
LiFePO4 Solar Energy Storage System / Double Conversion UPS

The aim of developing this was to make an ultimate system to power my electronics under all situations. The system is able to make use of any solar input that is available, with the remaining power requirements made up from the AC input. The AC charger is set to 13.2V, which keeps the battery from going below ~50% state of charge. That way there is always power available, even when the AC grid is not available and solar is insufficient. The unit is 80-85% efficient as a double conversion UPS, with ~94% efficiency on the AC charger and ~90% efficiency on the inverter. When solar generation is greater than load requirements, excess energy is stored in the battery for use later in the day/night. This system took a long time to design and build, everything was planned out in Fusion360 beforehand to ensure I was happy with it before purchasing components.

<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141225.jpg">

Features: 
* Battery: LiFePO4 4S2P 12.8V 2.3kWh
* AC Input: 240V 400W
* Solar Input: 100V 400W
* AC Output: 240V 1000W
* DC Output: 12V10A Cigarette Port x2, USB 5V2.1A x2, USB QC3.0 x1, USB Type C PD3.0 18W x1
* Temperature controlled, always running silent fan 
* Coulomb counting state of charge meter
* Active cell balancing module
* Portable with wheels, mass ~30kg so it can be lifted up stairs
* Monitoring displays for Battery, AC Output, AC Input and Solar input. 
* Battery is lightly compressed using additional ETFE sheets between the cells. 
* Threaded rods redistribute much of the battery weight to the case walls, also greatly improving rigidity of the battery and case.

Related resources: 
* Cell terminal covers / shrouds: https://www.thingiverse.com/thing:4567648
* Battery management system display: https://github.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay

3D Model in Fusion360: 
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/fusion1.JPG">
System electrical diagram:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/schema1.JPG">
AC Inputs & Outputs:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141238.jpg">
Monitoring displays:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141254.jpg">
DC Inputs & Outputs:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141341_HDR.jpg">
Inside:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141410.jpg">
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141421.jpg">
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200912_141442_HDR.jpg">
The cells on the bench:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200819_163244_HDR.jpg">
3D Printing cell holders / shrouds:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200819_163305.jpg">
Thermal image when under 800W Inverter load:
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200825-133709-edit.jpg">
Thermal image when AC input is at maximum (400W):
<img src="https://github.com/vagueDirector/LiFePO4_SolarSystem/blob/master/20200825-143747-edit.jpg">

