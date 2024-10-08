# TT4U
Teletype port to 4U system

After mounting the complete DIY Terminal PCB you can choose to flash the firmware first or after mounting the I/O pcb. 
I rather flash it first and to do so I suggest to mount the USB A connector on the Terminal PCB to be able to flash.
Don't solder the outer ground brackets of the USB conenctor on the Terminal, because this connector has to be mounted on the I/O pcb.

Flashed or not, you will have to mount an army of male pins on the terminal.

![alt text](https://github.com/themangoest/TT4U/blob/main/TT4U-pin%20header-Layout.jpg)

All in yellow needs a male pin, red are 2 seperate wires and blue is an optional drill hole for more mechanical stability.

Pins needed are:
- 23x 1 pin
- 1x 3 pin
- 1x 20 pin

At this point, you can take off all the SMD leds that are on the terminal PCB. This will reduce your power consumption.

When you solder both I/O and terminal together, take them apart to continue with the I/O board.

<B>Work to do on the I/O board:</B>
- Mount the 6mm M2,5 standoff
- Mount your USB A connector
- Leave the 2 wires in the middle of the USB connection on the I/O board.
- Mount your B10K pot
- Solder a 20pin male header on the screen.
- Mount the header of the screen in the solder holes and keep the screen even to the I/O pcb and solder it in.
- Keep your THT LED (4 blue and 4 red) aside for later.

<B>Work to do on the panel:</B>
- Mount all bananas
- Mount your switch

Now it is time to put in your leds, pay attention at he orientation. Square pad is the longest led.
After that mount the terminal PCB and solder the 2 USB middle wires back in.

OK, now time to mount the 4U power and I2C bus.



Mount the panel on the I/O board and solder all your LEDs, bananas and switch.
