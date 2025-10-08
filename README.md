# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
**full adder**

<img width="567" height="329" alt="image" src="https://github.com/user-attachments/assets/8b09ba30-0f1c-40ba-b9dd-215f975a67ac" />

**full subtractor**

<img width="442" height="314" alt="image" src="https://github.com/user-attachments/assets/ed193f64-287d-42c6-83b2-12d72949a405" />



**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Vishnu Priya A K  RegisterNumber:25018523
*/

**RTL Schematic**
**full aadder**

<img width="1209" height="609" alt="Screenshot 2025-10-08 133100" src="https://github.com/user-attachments/assets/4f06b402-ce66-4a0a-9662-f9df7a8d7892" />

**full subtractor**

<img width="910" height="361" alt="Screenshot 2025-10-08 133859" src="https://github.com/user-attachments/assets/43475bd0-6fd3-43a5-98ed-9402e8fc75af" />



**Output Timing Waveform** 

**full adder**

<img width="1904" height="737" alt="Screenshot 2025-10-08 133010" src="https://github.com/user-attachments/assets/6f03dfd2-5d5d-4b79-8d64-469cb99e8905" />


**full subtractor**

<img width="1919" height="728" alt="Screenshot 2025-10-08 133833" src="https://github.com/user-attachments/assets/05a600f0-82ee-43b5-b4c1-f997e67f79d4" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



