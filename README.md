# Mod7UpDown_Project
Modulo-7 Up/Down Counter made from digital logic ICs and a 7-segment display for output.

For this project, I designed a mod-7 up/down counter. I began by manually mapping a state transition table, and deciding which type of flip-flops I would use. I ended up with using 2 JK flip-flops for the first two bits, and a D flip-flop for the final bit.
Knowing the type of memory I was using, I used Karnough maps to map out state changes and wrote my logic equations.
Once the equations were written, I made sure they were correct by mapping the circuit in NI Multisim. When the digital simulation functioned, I shifted to hardware. 
After much debugging to check logic mistakes in my wiring, the board was completed. One switch, labelled "enable" would freeze or play the counting function of the system. The next, labelled "up/down" would stand as our switch to make the circuit count either up or down. The output was displayed on a 7-segment display, which i used a driver chip for since our output comes as binary. 
I also included 3 LEDs so that i could display the values in binary as well.

Links for demonstrations: Physical Hardware - https://youtube.com/shorts/s-LO0uAm8YY?feature=share Digital Simulation - https://youtu.be/uvryEuphGuE
