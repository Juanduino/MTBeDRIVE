# MTBeDRIVE

This is a eMTB motor-controller hardware repository. The concept is a uniform powerstage, with a standardized MCU pinmap.
The goal is to make a modular controller, which is able to easily swap bulk capacitors. Having the MCU (Micro Controller/Drivers/Step_down etc.) 
on a seperate layer from the powerstage, optimizes and focuses the cooling on the powerstage, being directly attached to a heatsink. 

You can say, the design seek´s a slim and compackt expresion, becource it is specifically designed with a MTB conversion in mind.

![ENCLOSURE](https://github.com/Juanduino/MTBeDRIVE/blob/main/img/Enclosure_top.jpg)

Specifically the interface is designed with the Portenta H7 (Dual Core MCU) in mind, but other MCU´s could euqually connect with the powerstage.'
For the erly_design, at this stage, the Portenta H7 is the only available choice for development on STM32H747. Later when the MCU´s emerges in stock, we can combine the Portenta H7 and driver/step_down layer in a custom PCB design. 

*
![ENCLOSURE](https://github.com/Juanduino/MTBeDRIVE/blob/main/img/Few_improvements.jpg)
*

Becouse the bulk capacitors has a limited lifetime, the overall system lifetime can be extended by detaching the bulk capacitor "bank". By making it modular, it can also vary en size. 


![ENCLOSURE](https://github.com/Juanduino/MTBeDRIVE/blob/main/img/MTB_eDRIVE.jpg)

*
There are many kinds of MOSFETS footprint´s, some with better propaties then other. Having a BASE design, with uniform dimensions and interface, makes it possible to reuse the independent parts, which can then later realign with other shapes. 
*

*
![ENCLOSURE](https://github.com/Juanduino/MTBeDRIVE/blob/main/img/NTC_ThermistorX3.jpg)
*



