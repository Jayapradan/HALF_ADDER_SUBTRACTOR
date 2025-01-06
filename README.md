## NAME: JAYAPRADAN M
## REG NO:24900886
## EXPERIENMENT 3 NAME: HALF ADDER SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**HALF ADDER**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**HALF SUBRACTER**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**TRUTHTABLE**

![WhatsApp Image 2024-11-28 at 11 11 59_ee79572d](https://github.com/user-attachments/assets/5de53b9d-eb73-4a99-b211-f5d9e8d7c4ea)

![WhatsApp Image 2024-11-28 at 11 12 01_70ffa8d7](https://github.com/user-attachments/assets/e6b245bd-7937-41e7-bb07-e9071ef31783)

**PROCEDURE**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**

![WhatsApp Image 2024-11-28 at 11 12 03_26c7f352](https://github.com/user-attachments/assets/e5b2f53a-5280-4724-8988-edc848100533)


**RTL**

![WhatsApp Image 2024-11-28 at 11 12 01_93371a87](https://github.com/user-attachments/assets/c482327e-ee0c-487b-a579-85624556c38c)

**TIMING DIAGRAM**

![WhatsApp Image 2024-11-28 at 11 12 02_9074dafb](https://github.com/user-attachments/assets/229147d3-fd50-4683-8aac-521639aec6d0)

**RESULT:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming verified successfully
