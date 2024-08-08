# Cross-Coupled-Voltage-Level-Shifter

A level shifter circuit is an integral part of any chip as it acts as the interface between multiple blocks on the chip which operate on different supply voltages independent of each other along with transistors having 
different threshold voltages. A level shifter circuit calibrates the voltage level of digital signals which are inputs/outputs of a particular block to avoid misinterpretation of logic levels 'high' and 'low'.

A cross coupled level shifter is the simplest conventional form of a level shifter which resembles a CVSL inverter. This project includes the schematic,layout with DRC and LVS clear,av extracted view after RC extraction 
which is used for post layout simulation to show the effect of parasitics which increases the average power consumed and delay, layout placement report and also layout after reading the GDSII stream file generated from 
the original layout. Here the voltage level is shifted from a peak of 1.2V to 2.5V and the output capacitance is taken as 250fF.
