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

![Screenshot 2024-12-08 203106](https://github.com/user-attachments/assets/e4723ddb-ad94-4047-8545-1ef7e5896aac)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

![Screenshot 2024-12-08 204913](https://github.com/user-attachments/assets/77c234e1-555b-498d-8725-36a065806d83)

Figure -02 HALF Subtractor

**Truthtable** 

![WhatsApp Image 2024-12-08 at 20 36 18_e3f78c44](https://github.com/user-attachments/assets/009464a2-0e81-45e6-ae38-306e95876e1d)

![WhatsApp Image 2024-12-08 at 20 36 47_371e71b4](https://github.com/user-attachments/assets/d6878c5f-6050-4eb5-9b0d-26a5ed06a101)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Dinesh.V
RegisterNumber: 24010667

![Screenshot 2024-12-08 203154](https://github.com/user-attachments/assets/1175ae8e-0ed7-4642-bebf-c56bd7daff21)

![Screenshot 2024-12-08 205119](https://github.com/user-attachments/assets/4465881a-1632-4f0d-a2ea-012bd4ae80fc)


**RTL Schematic**

**Output/TIMING Waveform**
![Screenshot 2024-12-08 203431](https://github.com/user-attachments/assets/4cc07093-ec10-4351-a3f4-38735f6f45d7)

![Screenshot 2024-12-08 205058](https://github.com/user-attachments/assets/66dc89eb-bb11-4bab-933d-85fc56a7383c)

**Result:**
Thus the truth table of Half Adder & Subtractor in Quartus || using Verilog programming are studied, verified and executed successfully.
