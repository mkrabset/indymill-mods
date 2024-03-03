My controller board running [a fork](https://github.com/mkrabset/grbl32) of GRBL on a STM32 [bluepill](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill.html).

Some (odd?) features :
* Use two 74245 bus transceivers for level shifting (3.3 to 5 volts) and voltage buffering. 
* Use a few 74 series logic chips (74LS32 quad OR-gate + 74LS08 quad AND-gate) for auto-squaring on y-axis.
* I use DM556 stepper drivers in my setup. Used the cheaper TB6600 earlier.
