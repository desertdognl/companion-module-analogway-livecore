# Help section for the AnalogWay Livecore module

With this module you can control all graphic switchers from the Livecore series by AnalogWay. Most popular models are Ascender and NeXtage. It is also possible to control stacked configurations or configurations with an output expander. In any case please use the IP of the master machine.
If you want to test your configuration, you can also connect to the Livecore simulator. If you use the simulator on the same computer as Companion use the IP the simulator runs on (default is 192.168.56.101), if you run the simulator on a different machine use the IP of that machine and you have to run AWGateway on that machine too.

Most commands are straight forward, only thing to mention is the screen selection for the global take command.
Before you can use the global take command you have to select the screens which will be affected by the command. The selection is stored in the device until it is changed. The screen selection for the third party protocol is independent from the screen selection of WebRCS, so you cant see in WebRCS which screens are selected for the take command of Companion.

This module uses always the default TCP port number of 10600 for control of the device. Make sure the port number is not set to something different on your Livecore machine.

**Available variants for AnalogWay Livecore**

* ACS4806
* ACS3204
* NXT1604
* NXT0802
* SMX12x4

**Available commands for AnalogWay Livecore**

* Take selected screens (Global take)
* Take single screen
* Load Memory
* Load Master Memory
* Set recall filter
* Freeze Input
* Recall Monitoring Memory
* Fullscreen Monitoring
* Select screens for global take
* Load confidence mode
* Switch input plug
* Send custom command
