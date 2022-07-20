Executing the program with the circuit:

As explained in the "encode_scheme.docx" file, first the instructions of the program should be encoded as stated in the file.
The encoded instruction should be written explicitly in the RAM as a Hexa-decimal number.The data/Input should be placed in
appropriate location(data/input and instructions should have different addresses).The RAM stores a 32-bit value and has 16-bit 
for address(which mean that there are 2(power 16) locations each of 32-bit).The Processor-memory interface is explained in the
"implementation.docx" file.The 'RESET' input field can be used to clear the values of all the registers and Register file
and also to clear the memory(RAM) after/before the execution of the program.Initially, the 'pc' register is made to point the 
starting location of program by explicitly writing the starting address of program into 'pc'.The 'ALU' and 'Register file' circuits
are seperatly implemented and are used in 'main' file.After executing the program the output can be viewed at appropriate location.

