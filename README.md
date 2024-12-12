### NAME:DINESH KARTHIK R
### REG NO:24900716
### HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

### AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### HALF ADDER:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

### HALF SUBTRACTOR:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

###  TRUTH TABLE:
![WhatsApp Image 2024-12-12 at 10 22 50 AM](https://github.com/user-attachments/assets/c392ae41-0566-4d35-b630-8be6319b8542)
![WhatsApp Image 2024-12-12 at 10 22 49 AM(1)](https://github.com/user-attachments/assets/1e6e33f6-00d5-43f9-8f5f-0b8c2ce51482)

### PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM:
![WhatsApp Image 2024-12-12 at 10 22 51 AM](https://github.com/user-attachments/assets/5c04e3ca-b931-47ea-b894-9c38eae4870e)


### RTL:
![WhatsApp Image 2024-12-12 at 10 22 50 AM(1)](https://github.com/user-attachments/assets/8b320f3e-60ed-4cbd-af8b-d4921a5b98c8)

### TIMING DIAGRAM:
![WhatsApp Image 2024-12-12 at 10 22 51 AM(1)](https://github.com/user-attachments/assets/3286c7d3-8fc5-487e-9bc1-e4d303ec65b4)

### RESULT:
