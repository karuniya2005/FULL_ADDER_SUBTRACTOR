# EX NO:4
<P align='center'> <b>Implementation-of-Full-Adder-and-Full-subtractor-circuit</b>

**DATE:**

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

**Procedure**
```
1.Follow the same steps as for the full adder.
 2.Draw the full subtractor circuit using schematic design.
 3.The circuit includes XOR, AND, OR gates to perform subtraction.
 4.Compile, simulate, implement, and program the design similarly to the full adder.
 ```
**FULL ADDER**

**Program:**

![alt text](<Screenshot 2024-04-27 103439.png>)

**RTL Schematic**

![alt text](<Screenshot 2024-04-27 103459.png>)

**Truthtable**

![alt text](<Screenshot 2024-04-27 103509.png>)

**Output Timing Waveform**

![alt text](<Screenshot 2024-04-27 103527.png>)

**FULL SUBRACTOR**

**Program:**

![alt text](<Screenshot 2024-04-27 103537.png>)

**RTL Schematic**

![alt text](<Screenshot 2024-04-27 103546.png>)

**Truthtable**

![alt text](<Screenshot 2024-04-27 103554.png>)

**Output Timing Waveform**

![alt text](<Screenshot 2024-04-27 103603.png>)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



