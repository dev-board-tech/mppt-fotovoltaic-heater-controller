# MPPT Fotovoltaic Heater Controller
 A compact fotovoltaic high power high voltage MPPT heater controller

A very compact heater controller that uses fotovoltaic panels in order to heat water in a boiler.

The project is developed around an Arduino nano V3 module using a BW OLED 128x64 SPI or TWI display.

The controller is designed to be configured working in BUCK or BOST mode thru changing the location of three jumpers.

The BUCK/BOST coil can be mounted externally using screws, the same the PV input capacitor, this allow for the board to be more compact decreasing the production price.

Include:

* One fan PWM output.
* Two onboard digital temperature sensors DS18B20.
* One wired NTC 10K temperature sensor wired to the heater.
* Onboard voltage reference TL431LP.
* Dedicated current sensor ACS758xCB-100B-PFF.
* One temperature exceeded output terminal.
* One RTC with backup battery because the controller is powered exclusively from panels DS1307.
* UART connector with 5V power.
* TWI connector with 5V power.
* Support three models of dedicated AC-DC/DC-DC inverter 95-385V to 9-12V for powering the board from panels HLK-PM12/HLK-5M12/RAC04-12SGA.
* BUCK inverter from 9-12V to 15-18V to efficiently drive the gate of the power MOS/IGBT MC34063AD.

