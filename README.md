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

**Procedure**

Write the detailed procedure here

**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
```
Developed by: Koppala Naveen
RegisterNumber:212223100023
```

**Full Adder:**

![image](https://github.com/koppalanaveen/FULL_ADDER_SUBTRACTOR/assets/152313952/7df9d93a-3f31-4743-aecd-70ff12ab5031)



**Full Subtractor**


![image](https://github.com/koppalanaveen/FULL_ADDER_SUBTRACTOR/assets/152313952/8edc9ab2-3f76-4565-aed3-77bfe6b126ce)



**RTL Schematic**

**Full Adder:**

![image](https://github.com/koppalanaveen/FULL_ADDER_SUBTRACTOR/assets/152313952/6311b695-1670-4d7e-98c2-9339a8dec80a)

**Full Subtractor**

![image](https://github.com/koppalanaveen/FULL_ADDER_SUBTRACTOR/assets/152313952/9a176ca6-1cf4-4378-93b0-5bbb80a2d602)

**Output Timing Waveform**

**Full Adder:**

![image](https://github.com/koppalanaveen/FULL_ADDER_SUBTRACTOR/assets/152313952/3d5075a0-18a2-487b-bd17-262c9162fad8)


**Full Subtractor**

![image](https://github.com/koppalanaveen/FULL_ADDER_SUBTRACTOR/assets/152313952/99a16925-11c4-4dd6-b389-e439d7797c38)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.

