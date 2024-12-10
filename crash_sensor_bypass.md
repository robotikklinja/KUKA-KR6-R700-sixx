# KUKA robot crash sensor bypass

![Connections_in_box.jpg](bilder/Connections_in_box.jpg)

![Schematic of sensor pins](bilder/schematic_sensor_pins.jpg)

We need a bypass for this crash sensor, so that we can run the robot when it has triggered.

It is a 24V NC PNP signal, max 100mA. The sensor is expensive so we include a diode to protect it from being effected by reverse current.

EDIT: Replacing the diode with 1k resistor makes it safer, if somebody wires it wrong.

We have made a box for the connections, it has a momentary switch.

![Crash_Sensor_NC.jpg](bilder/Crash_Sensor_NC.jpg)

Crash_Sensor_NC

![crash_sensor_triggerd.jpg](bilder/crash_sensor_triggerd.jpg)

crash_sensor_triggerd

![Crash_sensor_bypassed.jpg](bilder/Crash_sensor_bypassed.jpg)

Crash_sensor_bypassed

[Falstad circuits code, download](bilder/Robot_crash_sensor_bypass.txt) and [Open in https://www.falstad.com/circuit/](https://www.falstad.com/circuit/)

Status:

Avaiting the cable to connect to the robot.


