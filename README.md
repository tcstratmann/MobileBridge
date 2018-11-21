#Mobile Bridge - A Portable Design Simulator for Ship Bridge Interfaces

![Photo of Mobile Bridge set up as Ship Bridge Simulator](images/MobileBridge.jpg | width=500)

The Mobile Ship Bridge is a configurable ship’s bridge system in which new eNavigation technologies can be tested and demonstrated. In particular new interaction concepts are within the focus of the development. This includes both, the providing of information to nautical personal as well as new control concepts.
The portable structure of the system allows a straightforward demonstration of these concepts in a real system environment, e.g. on real ship bridges as the system can be connected to the sensors on board of the ship in parallel with the real systems. An additional vision system supports the design, development and demonstration of these interaction concepts within a virtual environment.

The System consists of two main components: The Mobile Bridge itself and the vision system.
 
The mobile bridge system is separated into three different segments that can be combined and connected with each other. Each of these segments is buildup of one information and one control element. Whereas the information element is realized as a multi-touch monitor. The control element could be either a multi-touch monitor or a set of bridge control elements like thrust levers or a steering "wheel". The multi-touch control element enables the testing of new concepts for virtual handles and controls. See the [Virtual Handles](https://github.com/tcstratmann/VirtualHandles) repository for an example of freely configurable virtual handles and information displays we use with our bridge elements.

To further ensure the portability of the bridge system, the hardware of the vision system is totally decoupled from that of the bridge system. 
The vision system is used to visualize a traffic simulation within a 3D environment. For this purpose the vision system consists of three additional displays, which are realized by a full HD curved television system, but can be easily replaced by utilizing video projectors.

Combined the two components form a fully functional Ship Bridge Simulator using either the open source Simulator Software [Bridge Command](https://bridgecommand.co.uk/) or our own in-house developed traffic simulation and models.

## Build

- Per Bridge Element you will need the hardware listed in the [Bill of Materials](BOM.md), we recommend building 3 units
- Use a lasercutter ([Settings](LasercutterConfig.md)) to cut the faceplates (([CAD files](CAD/)))
- Cut a 22 x 4 cm rectangular hole into the back of each flight case for the connectors
- Cut a 1 cm diameter hole into the front right corner of the flight case for the power button
- ...

