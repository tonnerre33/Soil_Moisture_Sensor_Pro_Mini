# Soil Moisture Sensor Pro Mini

# What is this ?

It's the same project than [this ](https://www.openhardware.io/view/338) but without smd components.

I think it's a good node for the beginers ;)

The CR123A is replaced by 2xAAA batteries.

You can order the pcb here : https://PCBs.io/share/z5YOZ


![Soil Moisture Sensor Pro Mini](https://www.openhardware.io//uploads/58a0ad35d1cdc0b03cebe777/image/IMG_6591.JPG "Soil Moisture Sensor Pro Mini")

# Features?
* Send Soil moisture mesure every hours
* Send Battery Level every hours if the value has changed
* Send Battery voltage every hours if the percentage has changed


# Compatibilies ?
* Mysensors Library 2.0.0
* PCBs v1.1.x compatibles with SoilMoisture_Sensor_Pro_Mini_v1.1.x Sketchs


# Logs PCB :

## V1.1
* 21/02/2017 = Fabrication V1.1 by PCBs.io => Awaiting Panelization
* 27/02/2017 = Fabrication V1.1 by PCBs.io => In Fabrication
* 08/03/2017 = Fabrication V1.1 by PCBs.io => Shipped
* 15/03/2017 = Fabrication V1.1 by PCBs.io => Received
* 15/03/2017 = Assembly and Test => OK

# Logs Sketch:
## V1.1.2
* Add default values
* Do not send moisture to the controler if she didn't change more than 1%
* Change Low Fuse example

## V1.1.3 - In progress
* Fixed "Do not send moisture to the controler if she didn't change more than 1%"
* Added possibility to blink the "info" led when insufficient moisture
* Added possibility to blink the "warning" led when insufficient battery
* Added possibility to use this node without controler (need mysensors >= 2.1.0)
* Disable smartsleep when not OTA used (increase battery life)
