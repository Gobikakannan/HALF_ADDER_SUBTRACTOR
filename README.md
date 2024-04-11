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

![exp3 table add](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/bad572ca-0b90-47e1-a9e7-16039d948527)

![exp3 tsable  sub](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/4cfa7479-4999-4cd7-addf-b9b5deeecce0)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![exp3 code](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/c570829f-0dac-42ed-a77f-64d4f68a68d3)

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Gobika K
RegisterNumber:212222050013

**RTL Schematic**

![exp3 rtl add](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/0437572a-7931-4374-a05a-34e9f11e2126)
#### Half Subtractor:
![exp3 rtl sub](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/950927bc-52a4-42ad-9436-913368b412eb)

**Output/TIMING Waveform**
#### Half Adder:
![exp3 output add](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/320d84d8-8e74-4437-b191-ea20991cd421)

![exp3 output sub](https://github.com/Gobikakannan/HALF_ADDER_SUBTRACTOR/assets/163496346/afde4f77-3dcf-4e38-ad4e-d48dea07fe82)

**Result:**
Thus the half subtractor and half adder circuits are designed and the truth table is verified using quartus software.
