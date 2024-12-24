# Addition-Subtraction-Logical-operations
For addition and subtraction , I have used the same circuit and the only change in carry_in.
4 bit parallel full adder circuits are made.
But for the second binary number,XOR Gate is used along with Carry_in as the other input.
To control the input dip switches are used.
1st no.-  A
2nd no.-  B
So, for addition carry_in=0 
    B XOR 0 = B
    Here 2nd no. goes into the full adder circuit as it is.
     
for subtraction carry_in=1
    B XOR 1 = ~B
    Here 2nd no. goes into the full adder circuit as 2's complement of B.
 I have used common anode 7 segment display. The output of each LED will be 0 or 1. So,b,c segment of LED will always glow. If the output(sum) will be 0 then a,d,e,f segments of LEDs should glow. Or else if the output would be 1 ,then these segments should not glow. So,the outputs are connected to a,d,e,f segments of LEDs.

For AND,OR,XOR Operations there are 8 switches(4 for each 4-bit binary no.).One end of switch is connected to the Vcc=5V and the other end is connected to respective gates.
7 segment common anode LEDs are used to show the output. The connection in the LEDs are done as stated for addition and subtraction.
