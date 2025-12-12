AIM:

To design a Full Adder circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin

Carry = AB + ACin + BCin


<img width="716" height="339" alt="Screenshot 2025-12-12 105745" src="https://github.com/user-attachments/assets/05a8b440-3db9-4f83-ba8b-6b2635e232f6" />

Truthtable

Procedure

* A full adder requires three inputs: two bits to be added (A and B) and an input carry from a previous stage (\(C_{in}\)).
* The two outputs are the sum (S) and the carry-out (\(C_{out}\)). 
* The sum output can be achieved with a 3-input XOR gate, which calculates \(S=A\oplus B\oplus C_{in}\). 

Program:

/* Program to design a full adder circuit and verify its truth table in quartus using Verilog programming. 
Developed by:GOKULAVANI.R

RegisterNumber:25017080 */

RTL Schematic

Output Timing Waveform

Result: Thus, the Full Adder circuits are designed and the truth tables is verified using Quartus software.
