Battery Interface Module (BIM)
========================

Battery Interface Module is a 36-cell lithium battery cell monitor with built-in balancing and CAN communications.

![Image of BIM](https://raw.githubusercontent.com/aaronbeekay/Battery-Interface-Module/master/Documentation/BIM%20r02%20cut%20out%20400px.png)

It's built to go on [Buckeye Current](http://current.osu.edu/)'s RW-series electric racing motorcycles. The latest version (v1.0) was installed on RW-2x, an Isle of Man road racer.

The Battery Interface Module is built on the TI BQ76PL536A battery-monitor IC. Some features include:

* Voltage monitoring of up to 36 battery cells at precision of ~1 mV
* Thermistor connections for cell temperature monitoring
* Onboard cell balancing (~100 mA)
* Onboard host processor to control battery interface, control balancing, and transmit data over CAN
* Wide input voltage range (4-40 V)
* PCB temperature monitoring to prevent overheating from cell balancing
