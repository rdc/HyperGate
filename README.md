HyperGate Client Scripts
========================

Client scripts for HyperGates on the HyperGate Network from http://TheHyperGates.com

See the wiki for some documentation and features: https://github.com/rdc/HyperGate/wiki




June 24th, 2013

For the past four years, these scripts have performed flawlessly on literally thousands of OpenSim simulators connected to the HyperGrid. Literally hundreds of thousands of HyperGrid links have been provided to HyperGrid travelling avatars over that time.

One must remember that the HyperGrid is just the 'potential' to federate. Once HyperGrid destinations have been networked, only then are they truly federated.

With this in mind, if a region is connected to the HyperGrid but not connected to the HyperGate Network, is it really on the HyperGrid?


Today the HyperGrid Network is by far the largest teleport network in the entire Metaverse, including the largest teleport networks in SecondLife (tm). In fact, today the HyperGate Network is larger than the two largest Secondlife (tm) teleport networks combined. ( http://www.alpha-fox.com/about/ & http://opengate.ma8p.com/list.cgi )



Functionality
=============

These scripts can be used to connect your own HyperGrid teleport devices and HyperGrid link boards to the HyperGate Network.

These scripts have a modular design. This makes it easy to add and replace functionality. Adaptor modules can also be created to interface with any in-world device or HUD.

We invite you to improve and expand on this code to help bring the HyperGate Network into the next level in HyperGrid existence.


These scripts provide several functions:

- register the HyperGate/object/device on the HyperGate Network
- send KeepAlive requests to the Network to indicate that the HyperGate is still on-line and accessible
- communicate with the Network to receive data used to populate a set of menus that contain HyperGrid destination details
- other data such as News can also be retreived from the Network


This code has unlimited uses. It can be used as a basis to network ANY inworld objects to share information and data.



Notes
=====

The "Updater" functionality found in our original HyperGate v0.7.3 has not been included in this repository and related source code has been removed.


Technically, the "ThisGrid" functionality in the client/HyperGate is working. Although it is dependent on some legacy code that resides on the HyperGate Network server. We have no immediate plans for updating the "ThisGrid" reated code on the server side. If/when we do, the "ThisGrid" functionality will automatically be restored to all existing HyperGates/objects that are using these scripts.



Installation
============

Perform these instructions inworld.

1. In the root prim of your HyperGate/Teleport device/Object, create a new script named '_core' and paste into it the contents of the file named '_core' that can be found in this repository.

2. Repeat the same process for the rest of the files in this order: _dial, display, init, list, menu, monitor, settings



Code Documentation
==================

This code is far from documented. If you would like explanations or if you have questions, please feel free to ask. I will do my best to answer them. I am also willing to work together to document the code.



Error reporting
===============

If you find any errors that you would like resolved, feel free to report them here: https://github.com/rdc/HyperGate/issues
I cannot commit to fixing any errors, but if they are listed here, then maybe others can fix them.

Before reporting any errors, please be sure that your simulator is not at 100% CPU when the scripts are loading. If your CPU is 100% while the scripts are loading, it could cause the scripts not to load completely. 

This is a "heavy" set of scripts, the number one cause of these scripts not working is simply not enough CPU resources on the simulator.



Troubleshooting
===============

If you experience some issues with some of the modules being stuck in a "Waiting to Initialize.." state or similar, try resetting the '_core' script and/or the script for the module that is stuck.




All the best,

Zvi ben Yaakov (a.k.a rdc)
email: hypergate.src@infosoc.net
web:   http://TheHyperGates.com
