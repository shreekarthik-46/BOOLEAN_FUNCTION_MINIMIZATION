# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by:Subashree Karthikeyan RegisterNumber:24900650


**RTL realization**

**Output:**

**RTL**
![rtl2](https://github.com/user-attachments/assets/bc0e7a01-a2bb-48ce-a4e5-fe5b5dbfd63d)


**Timing Diagram**
![time2](https://github.com/user-attachments/assets/5137df68-e778-4402-a87b-304b1a47d9b9)


**Result:**
The implement the given logic function verify its operation in Quartus using Verilog programming.


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

