Battery Interface Module (BIM)
========================

Battery Interface Module is a compact, 24-cell lithium battery cell monitor with an onboard microcontroller and CAN communications.

![Image of BIM](https://github.com/aaronbeekay/Battery-Interface-Module/blob/main/Documentation/Battery%20Interface%20Module%20v2%20600x400.jpg?raw=true)

*Image: Battery Interface Module v2*

It's built to go on [Buckeye Current](http://current.osu.edu/)'s RW-series electric racing motorcycles. The latest version (v2.0) is designed to integrate with RW-3, a purpose-built racer for the Pikes Peak International Hill Climb.

The Battery Interface Module is built on the TI BQ76PL536A battery-monitor IC. Some features include:

* Voltage monitoring of up to 24 battery cells at precision of ~1 mV
* Thermistor connections for cell temperature monitoring
* Onboard host processor to control battery interface, control balancing, and transmit data over CAN
* Wide input voltage range (4-40 V)
* Isolated interface to battery voltage monitors

You can read more about the Battery Interface Module in the [Battery Interface Module design report]( https://github.com/aaronbeekay/Battery-Interface-Module/raw/main/Documentation/Battery%20Interface%20Module%20report.pdf).
