# LaunchPad-TM4C123

I am a beginer on Embedded C, but I want to contribute with the little information I know.
I am not using the third device libraries as the main aim of this repository is to give examples on how to program the LauchPad board by directly accessing its registers. I have always used the functions already provided by third libraries and had no idea how to actually program the registers to get the microcontroller to do what I required. For example, I could use the fuctions provided by third libraries to switch a a led by providing only the pin number (PIN_1) and its direction, but I did not know how to define the actual register.

The first example will be how to configure the GPIOs so the microcontroller can read a switchbutton to switch a LED on/off, accordingly. 
