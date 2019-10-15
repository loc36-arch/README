# README: System architecture README

Loc 36 is a system that allows students of LAUTECH (Ladoke Akintola University of Technology) to know the power supply status of locations around them.

# How it works?

Loc 36 relies on three elements to function:

* power supply sensors,
* servers,
* and interfaces (app, etc)

A sensor is connected to the power supply of a location. And this 
sensor periodically transmits the state of that location to a 
server. This server stores the records that have been received so 
far. And when the user wishes to know the power status of 
locations, their interface requests it for them (from the server), 
and the interface presents it to them.
