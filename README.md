# PCB-layout-for-dual-power-supply-circuit
Dual power supplies are circuits that generate two different output voltages from a single input  source. There are numerous types and configurations possible. The most common configuration  provides two different positive DC voltage outputs or two equal magnitude and opposite polarity DC  voltage outputs
To convert 220V AC supply in to +12V and-12v DC supply, that is why it is named Dual Power Supply as we get positive and negative 12v power supply at the same time.This can be achieved in simple three steps:
Firstly, 220V AC is converted into 12V AC by using simple step-down (220V/12V) transformer.
Secondly, output of this transformer is given to the rectifier circuit, which will convert the ac.supply into dc supply. The output of the rectifier circuit that is DC contains the ripples in the
output voltage.To filter out these ripples, capacitor of 2200 uf, 25V is used.
Lastly, the output of the capacitor that is pure DC is given to voltage regulator IC 7812 and IC7912 which will regulate the output voltage at 12V and-12V DC, despite the change in input voltage.
 
 Components Required:
 Centre tapped transformer (220V/12V)
 PowerDiodes (6A)– 4No.
 Capacitor (2200μF, 25V)– 2No.
 Voltage regulator (IC 7812 & 7912)
 Toggleswitch
 DCload(DCmotor)

Applications:
Operational amplifiers need two power sources (usually one +ve source and one-ve source) because the op-amp must operate in both polarities of the incoming signal. Without the negative source, the op-amp will not swing into action during the negative cycle of the signal. So that signal portion's output will "clipped", that is, remain at ground itself; which is obviously not recommended.
If DCmotors are used as a load, then for +12V it will rotate in clockwise direction and for 12V it will rotate in opposite direction. For example, motors which are used in toys (car, bus etc), will move forward in case of +12V and it will move reverse in case of-12V.
