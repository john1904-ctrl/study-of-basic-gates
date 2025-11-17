### study-of-basic-gates
### NAME:M.JOHNPALL
### REFNO:212224040140
### DATE:19/04/2025


**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate
**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming
Developed by:John pall.M RegisterNumber: 212224040140
 ```
module exp1(A,B,C,D,E,F,G,H,I);
input A,B;
output C,D,E,F,G,H,I;
and(C,A,B);
or(D,A,B);
not(E,A);
nand(F,A,B);
nor(G,A,B);
xor(H,A,B);
xnor(I,A,B);
endmodule

```
 
**Logic symbol & Truthtable**

**RTL realization Output:** 
![Screenshot 2025-04-25 234847](https://github.com/user-attachments/assets/33aaa97f-0e93-44cb-b6fc-946b8e350489)


**RTL**
![image](https://github.com/user-attachments/assets/43b0ef4d-aa59-425b-a932-4eaea294e316)


**Result:**
Thus the truth table of logic gates (AND,OR,NOT,NAND,NOR,XOR,XNOR) is successfully implemented and verified using verilog programmming in Quartus II.

