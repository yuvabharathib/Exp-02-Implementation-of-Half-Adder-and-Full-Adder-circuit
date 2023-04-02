# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
```
Developed by: YUVABHARATHI.B

RegisterNumber: 212222230181 

Half adder program:
module fulladd (a,b,sum,carry);
input a,b;
output sum,carry;
assign sum = (a^b);
assign carry = (a&b);
endmodule

Full adder program:

module fulladd (a,b,c,sum,carry);
input a,b,c;
output sum,carry;
assign sum = (a^b^c);
assign carry = ((a&b)|(a^b)&c);
endmodule
```


### Output:
### RTL: 
![image](https://user-images.githubusercontent.com/113497404/229346940-025a9f14-2b5b-4aed-9ddb-fc6cf8be0721.png)

# FULL-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229346979-801941b7-800c-4eae-9c56-90e6c71b8358.png)

# RTL
# HALF-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229347106-503e56ff-205e-4c39-97f1-0586dd2f6fb9.png)

# FULL-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229347246-1d3b0045-52a4-4759-b513-38187f0a648e.png)

### TIMING DIAGRAM
# HALF-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229347315-0b1a0eb9-6ded-479f-a19e-3927bffdf38a.png)

# FULL-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229347335-0ad94e2a-a4d0-4bf2-a719-50e172d50b48.png)

### TRUTH TABLE 
# HALF-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229347372-4a4ece1d-56f0-4e92-bb84-277bf62d7d75.png)
# FULL-ADDER:
![image](https://user-images.githubusercontent.com/113497404/229347396-65edff6f-1605-47b7-a19e-8b2dbaf3904f.png)


### Result:
Thus the Implementation of Half Adder and Full Adder circuit are studied and the truth table for different logic gates are verified.
