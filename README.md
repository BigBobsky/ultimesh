# ultimesh
A meta mesh network engine manager

The goal of this project is to provide and deploy a kind of Software Defined Mesh through with extended features :
- heterogeneous link layers (802.11, ethernet, LTE, ...)
- a default 802.11s and LTE metrics implementation (based on nl80211 and QMI) 
- metrics translocations between interfaces : usefull for some use cases such as applying a wireless gateway type link to an exported wired link (possible through XML configuration file)
- C++ API to easily implement new business specific metrics
