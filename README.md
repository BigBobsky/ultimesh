# ultimesh
A meta mesh network engine manager

The goal of this project is to provide and deploy a kind of Software Defined Mesh through with extended features :
- heterogeneous link layers (802.11, ethernet, LTE, ...)
- a default 802.11s and LTE metrics implementation (based on nl80211 and QMI) 
- metrics translocations between interfaces : usefull for some use cases such as applying a wireless gateway type link to an exported wired link (possible through XML configuration file)
- C++ API to easily implement new business specific metrics

This repository will be populated soon with :
- Ultimesh core engine
- OpenWrt feeds for integration
- Yocto recipes and layer for integration
- Series of mesh network engine patches to be applied to work with Ultimesh
