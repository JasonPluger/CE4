###Computer Exercise 4
#####Analysis
######Program 1:
The goal of PRISM program 1 was to simply store values in certain memory locations. When approaching this problem, I understood what I had to do conceptually, however I initially had difficulty understanding how to use the PRISM computer to complete the task at hand. C3C Weisner helped me by explaining that when using the STA opCode, I have to place a value in the operand location in the ROM that is the same as the label used inside the correct RAM address location.

######Program 2:
For program 2, before I started coding, I created pseudo code on paper that helped me rationalize what we were trying to do and then translated my pseudo code to opCodes and then implemented it in the programming wizard. My pseudo code consisted of steps: 1)Grab value from RAM, 2) Double the value in the Acc, 3) subtract 4 from the value in the Acc, 4) Output the value in Acc to Port 2. As simple as this was, it helped me cut out the extraneous information in the CE4 document. 

######Program 3: 
For program 3, I took a similar approach to that of Program 2. I created pseudo code that helped me break the problem down into easy-to-accomplish tasks. My steps were as follows: 1)Read from Input Port 3, 2)Display input on Output Port 0, 3)Subtract 1 and display that on Output Port 1, 4)Subtract 1 and display that on Output Port 2, 5)Add 1 to the current value and loop back to step 2 above. I then went through each step and assigned the appropriate opCode to each stop and then implemented it in the Programming Wizard.


Documentation: 1Apr14: C3C Weisner: Explained the syntax of the STA opCode in saying that the operand used in the ROM has to correspond with the label used in the RAM memory location. 
               2Apr14: C3C Hayden: Explained that when adding a negative value to a hex value, instead of having to temporarily store the value in memory and do the arithmetic inside the accumulator and then adding the two values together, we can simply use the 2's complement of the positive number we're trying to subtract.
