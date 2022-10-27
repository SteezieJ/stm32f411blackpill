# stm32f411blackpill
This simple task sets up the blackpill with two buttons on EXTI GPIO lines to handle interrupts and toggles an external LED connected. 
see https://www.youtube.com/watch?v=6IjaqipSops and https://www.youtube.com/watch?v=UtkszckecV8 for nice explanation. <br>
Setup that is done:<br>
-The clock timer has been set, but optional.<br>
-The LED is an input on PA1 to ground<br>
-The button is connected to PB2 with the other two button line to the boards Ground and 3.3V.<br>
