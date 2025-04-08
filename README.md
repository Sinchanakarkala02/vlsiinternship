# vlsiinternship
new repo for vlsi internship

BASIC DETAILS:
Name: Sinchana

College: Mangalore institute of technology and engineering 

Email ID: sinchanah022004@gmail.com

* About task1 :Installed Ubuntu through VirtualBox. Wrote code to find the sum of numbers from 1 to N(100). Additonally executed assembly level program and verified the results .

* About task2 :
I started by writing a simple C program to add two numbers and saved the file as add.c. Afterward, I compiled it using gcc add.c and executed the program with ./a.out. Additionally, I compiled it using spike pk add.o for further analysis.  
Next, I performed a RISC-V object dump for both -O1 and -Ofast optimization levels to examine the generated assembly code.
Using the Spike RISC-V simulator with the command spike -d pk add.o, I analyzed the register values and observed how different accumulators stored the results.
Then,  took snapshots of the outputs and uploaded them to my GitHub repository.  

* About task4 :
  In GTKwave, obtained a waveform ( about signals) :
  For EX_MEM_IR[31:0] = 02208300 : add instruction :-  1 + 2 = 3.
   For EX_MEM_IR[31:0] = 02209380 : Sub instruction :- 1 - 2 = -1.
   For EX_MEM_IR[31:0] = 0230A400 : BITWISE AND  instruction :- 3 & 1 = 1    i.e,  0011 & 0001 = 0001.
    For EX_MEM_IR[31:0] = 02513480 : BITWISE OR  instruction :- 2 | 5 = 7    i.e,  0010 | 0101 = 0111.
