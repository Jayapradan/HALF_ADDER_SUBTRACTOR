### NAME: JAYAPRADAN M ###

### REG NO: 24900886 ###

### EXPERIMENT 3 NAME: HALF_ADDER_SUBTRACTOR ###

Implementation-of-Half-Adder-and-Half Subtractor-circuit

### AIM: ###

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENT REQUIRE: ##

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### HALF ADDER ##

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

### HALF SUBRACTOR ##

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

### TRUTH TABLE ##
![ex 3 5](https://github.com/user-attachments/assets/ae20ebdb-e2ca-4d95-b349-126b393594ab)



![ex 3 6](https://github.com/user-attachments/assets/cc355c21-02e7-4100-85be-2985df9c6b97)

### PROCEDURE ##

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM: ##

![ex 3 9](https://github.com/user-attachments/assets/713b3c11-f7fd-41c7-ad08-fc9ba61aa670)



### RTL:  ###

![ex 7](https://github.com/user-attachments/assets/b445725e-e6c6-44d4-9470-b51a46b0944f)

### TIMING DIAGRAM: ##


![ex 8](https://github.com/user-attachments/assets/aea8482a-b361-4e49-a9bf-58c71c9cc057)

### RESULT: ##

