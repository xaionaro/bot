Architecture
============

Overview
--------

Components:

* sensor
* DB
* preprocessor
* detector
* strategist

Connections:

* FX -> sensor -> DB
* DB <-> preprocessor
* sensor -> detector
* DB <-> detector -> strategist
* DB -> strategist -> FX

Sensor
------

Sensor is just a logger and event pusher

