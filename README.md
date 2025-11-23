# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

half adder

<img width="490" height="264" alt="image" src="https://github.com/user-attachments/assets/a62eef85-fe22-4b81-b986-550990a09a1b" />

half subtractor

<img width="563" height="246" alt="image" src="https://github.com/user-attachments/assets/b69eabd0-766a-472b-98e1-e2e90d1aacf0" />


/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:devi.s RegisterNumber:*/25004804

**RTL Schematic**

half adder
<img width="993" height="659" alt="image" src="https://github.com/user-attachments/assets/850be3ea-24c3-44c2-8bf4-abfff06c74af" />

half subtractor

<img width="1600" height="999" alt="image" src="https://github.com/user-attachments/assets/1220056a-04c1-431d-ba24-92b686594e6f" />



**Output/TIMING Waveform**

half adder

<img width="1600" height="998" alt="image" src="https://github.com/user-attachments/assets/1ecf2e60-b939-4b4f-8e12-3cac652993c3" />

half subtractor
<img width="1600" height="999" alt="image" src="https://github.com/user-attachments/assets/4835079f-94ee-4ef7-9aca-6c272df7c6c1" />


**Result:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
