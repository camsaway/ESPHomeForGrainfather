# ESPHomeForGrainfather
Provide the configuration YAML to integrate a Grainfather Connect Bluetooth to Home Assistant using ESPHome and an ESP32 board

1. Create a new device in ESPHome with an ESP32 board.
*NB. you need to set the BT MAC address of your personal grainfather*
(Maybe someone can tell me how to dynamically work this out in ESPHome from the BT device name)

2. Create a new dashbaord with the dashboard.yaml

To Do:
* Get a timer working
* Dynamically detect GF device
* Ability to load recipe steps
