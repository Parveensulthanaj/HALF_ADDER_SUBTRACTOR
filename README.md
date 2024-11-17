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

![tt A](https://github.com/user-attachments/assets/fd3b64be-bc46-49e1-9436-2fe5fec317f5)

![tt B](https://github.com/user-attachments/assets/ae3c3567-24ac-4569-955f-63b65602f11d)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
![half adder code](https://github.com/user-attachments/assets/8aa0e79c-1d0b-4911-b1b2-2529fd0ef147)

![half subtractor code](https://github.com/user-attachments/assets/548a617b-a053-41cd-80e3-33763205b70c)


Developed by:Parveen sulthana  RegisterNumber: 24900218*/

**RTL Schematic**

![half adder d1](https://github.com/user-attachments/assets/541bdaab-4e1c-4df8-8748-65afb08bcf51)

![half subtractor d2](https://github.com/user-attachments/assets/7f4f38e8-238d-49f9-9b37-1325ffbc7f74)

**Output/TIMING Waveform**

![half adder](https://github.com/user-attachments/assets/83db17c5-455e-405d-bcad-4f5ce0a56984)

![half subtractor](https://github.com/user-attachments/assets/178c7179-1e74-4a6c-b305-7b165e8fb5a4)

**Result:**
 Thus the half adder an dhalf subtractor are studied and the truth table,logic gates are verified.
