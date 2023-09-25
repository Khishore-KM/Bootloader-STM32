# Hi there ✋!

## What is this?
This is the repository of a bootloader with application for arm cortex-m4 controller.
In this repo, I have partitioned the flash memory of the controller and allocated spaces 
for bootloader and the application. The boot program gets initiated and then MSP calls
the starting address of the application.

#### Need for bootloader in Controllers:
There is no need for bootloaders for our personal applications in microcontrollers.
But when we are developing a product where it will have further updates and future upgradations,
every time we cannot connect JTAG/ST-Link based system for the product for multiple customers
right , having a bootloader solves the issue then you don't need a debugger or flasher for 
flashing the firmware. This will also reduce the security threats if someone tries to configure
or hack the system this kind of vulnerabilities will also reduce.




