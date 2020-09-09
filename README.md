# Arduino Mega 2560 with Optiboot Flash
*Write permanent data in flash memory at run-time on Arduino Mega 2560.*


## What is Optiboot Flash ?

...........


## Easy process to burn bootloader
We burn the optiboot_flash bootloader with an easy process using:
* Arduino IDE
* USB AVR programmer which emulates an STK500 on a virtual serial port
* An Arduino core for ATmega64, ATmega128, ATmega640, ATmega1280, ATmega1281, ATmega2560, ATmega2561, AT90CAN32, AT90CAN64 and AT90CAN128, all running Optiboot flash. 


## Required hardware and software
* <a href="https://store.arduino.cc/arduino-mega-2560-rev3" target="_blank">Arduino Mega 2560 Rev3</a> or <a href="https://www.amazon.fr/gp/product/B06XKZY117" target="_blank">Elegoo Mega 2560 R3</a>
![Elegoo Mega 2560 R3](images/elegoo-mega-2560-r3.jpg)
* <a href="https://www.pololu.com/product/3172" target="_blank">Pololu USB AVR Programmer v2.1</a> or equivalent
![Pololu USB AVR Programmer](images/Pololu-USB-AVR-Programmer%20v2.1.jpg)
* <a href="https://www.pololu.com/resources/software" target="_blank">Pololu USB AVR Programmer v2 Software and Drivers for Windows (.msi)</a> 
* <a href="https://www.arduino.cc/en/main/software" target="_blank">Arduino IDE for Windows</a> (release 1.8.13 at this time)
* <a href="https://github.com/MCUdude/MegaCore" target="_blank">MegaCore: an Arduino core for ATmega2560 running Optiboot flash</a>

In [./extras](./extras) folder youy will find software that We used the time I wrote this how-to:
* Pololu USB AVR Programmer Drivers 2.1.1.0 for Windows
* MegaCore source code in `MegaCore-master.zip` (get the <a href="https://github.com/MCUdude/MegaCore/archive/master.zip" target="_blank">latest</a>)

## Resources

* ........
* ........


## Author

**Jean-Michel _(Jim)_ FAURE** (July 9th, 2020)
* company: FAURE SYSTEMS®
* mail: *dev at faure dot systems*
* github: <a href="https://github.com/fauresystems" target="_blank">fauresystems</a>
* web: <a href="https://faure.systems/" target="_blank">Faure●Systems</a>