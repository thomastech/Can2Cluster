# CAN2Cluster 
Welcome to the CAN2Cluster project. It is a Arduino based CAN-Bus system for controlling Automotive Dashboard Instrument Clusters. Under development is a version that directly interfaces with a 2005-2009 Ford Mustang (six gauge) instrument cluster. Expansion to other CAN-Bus controlled dashboards should be possible by end-user development of the Arduino firmware.

![mustangcluster275](https://user-images.githubusercontent.com/10354989/50655679-b7a95a00-0f45-11e9-8c29-e3e9a20487e5.jpg)

### The CAN2Cluster Team Contributors
* Thomas B. (@thomastech, Project Originator)
* YOUR Name Here. Contribute to the project and join the cluster hacking team.

### Hardware Summary
* Arduino MEGA2560 R3.
* MCP2515/TJA1050 CAN-Bus Modules (2 pcs, for HS & MS CAN-Bus Ports).

### Project Status Timeline
* Dec-27-2018: Ordered CAN-Bus hardware.
* Dec-28-2018: Purchased Ford Mustang Instrument Cluster from online auto wrecker parts supplier.
* Jan-04-2019: Received Microchip CAN-Bus Analyzer Tool.
* Jan-08-2019: Received Instrument Cluster. CAN-Bus control working with Analyzer Tool.
* Jan-21-2019: CAN-Bus Test Software Video Demo now available. See Video Demo section below.
* Feb-01-2019: Gauge animation functions completed.
* **Feb-12-2019: Project complete. All Features are Working.**

### Notes & Comments
CAN2Cluster is a interactive desktop display that is best described as a car lover's art piece. It uses a 2009 Ford Mustang instrument cluster that has a two channel CAN-Bus communication port for control. Based on popular Arduino hardware, the CAN-Bus is used to animate the instrument cluster's gauges and warning lights.  

There's some interesting features too. An MP3 Audio Player is used to create the sounds of a rev'ing V8 motor that is synced to the gauges and indicators. For realism, an automobile ignition key is used to "start" the engine. There's also a hand-held IR remote that can control a dozen different functions. There's also serial terminal host access that allows the user to manually control the gauges and indicators.

The code could be adapted for a variety of applications, For example:
- Automobile Instrument Cluster Tester.
- Animated dashboard display for education, art, or entertainment.
- Dashboard for Race Gaming Cockpit.
- Custom Car Dashboard Conversions.

### Project Blog
Detailed information can be found in the Mustang Instrument Cluster Project blog:  
https://www.rc-cam.com/forum/index.php?/topic/4169-ford-mustang-instrument-cluster-project-introduction/


### Video Demos
<a href="http://www.youtube.com/watch?feature=player_embedded&v=fxD2akmYyDo" target="_blank"><img src="https://user-images.githubusercontent.com/10354989/52005499-b274f780-247e-11e9-9ec1-4138c7d364f1.jpg" 
alt="IMAGE ALT TEXT HERE" width="300" height="180" border="10" /></a>

### Resources
Sourceforge Ford CAN-Bus: https://sourceforge.net/p/ecu/wiki/canbus/  
### Alternate Search Terms:
CANBus, CANBuss, CAN-Buss, OBD, OBD2, OBDII
