## History

u360gts has been developed and maintained by users of the [FPV spanish community](http://www.aeromodelismovirtual.com/showthread.php?t=34530).

This project was born as **amv-open360tracker**, forked from the original project open360tracker developed by Samuel Brucksch. The firmware was originally designed to be run on Atmega328p and and Atmega2560 (8-bit AVR Microcontrollers used with Arduino) and was intended to be flashed on the popular flight controllers Cruise SE, as well as Arduino UNO, Nano and Mega using external IMU. The main idea was to build a DIY antenna tracker system by reusing those old flight controllers and the electronics devices we had left inside that box...

Users were requesting more and more funtions, protocols ... the code was growing and growing, and those microcontrollers had a big limitation on memory and hardware, so Raúl Ortega, the main contibutor of the firmware decided to migrate to 32 bit processors trying to keep in mind the same idea of reusing old electronics, giving the way to **amv-open360tracker-32bits** firmware version. The firmware had been developed for controllers based on STM32F series microprocessors, which fit the technical specifications of the popular NAZE32 flight controller (Flip32, NAZE32 rev5/rev6 ... with built-in compass, or ACRO version with external compass).

Later on Raúl Ortega decided to create a graphical user interface to configure the tracker and thought that would be good to uniffy both projects under the name ... **u360gts**... (u360gts for the firmware and u360gts-configurator for the configuration tool), and created a website as showcase and starting point for new users: [http://www.u360gts.com](http://www.u360gts.com).

[<< Go back](https://github.com/raul-ortega/u360gts/blob/master/wiki/index.md)
