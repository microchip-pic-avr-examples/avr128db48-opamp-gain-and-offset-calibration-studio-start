<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# Gain and Offset Calibration of the Analog Signal Conditioning (OPAMP) Peripheral

A new feature introduced in the AVR® DB MCU is the Analog Signal Conditioning (OPAMP) peripheral. The OPAMP peripheral can be configured as a PGA and in this example, the internal DAC and ADC are used to calibrate the gain and offset for the PGA. For more information on the calibration procedure, see the [application note](https://microchip.com/DS00003633).   

## Related Documentation

* [AN3633 - Gain and Offset Calibration of the Analog Signal Conditioning (OPAMP) Peripheral](https://microchip.com/DS00003633)
* [AVR128DB48 Curiosity Nano User Guide](https://www.microchip.com/DS50003037)
* [AVR128DB48 Device Page](https://www.microchip.com/wwwproducts/en/AVR128DB48)

## Software Used
* [Microchip Studio](https://www.microchip.com/mplab/avr-support/atmel-studio-7) 7.0.2542 or later
* Microchip Studio AVR-Dx_DFP version 1.6.76 or later
* For the MCC based MPLAB X version of this project, please go to [this repository](https://github.com/microchip-pic-avr-examples/avr128db48-opamp-gain-and-offset-calibration-mplab-mcc)

## Hardware Used

* [AVR128DB48 Curiosity Nano](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/EV35L43A)

## Setup

* No external hardware setup needed

## Demo Configuration
* Connect the AVR128DB48 Curiosity Nano to a computer using a USB cable
* Download the zip file or clone the example to get the source code
* Open the .atsln file with Microchip Studio
* Press *Start Without Debugging* (CTRL+ALT+F5) to run the application

## Conclusion
After going through this example you should be able to calibrate the gain and offset of the OPAMP configured as a PGA.
