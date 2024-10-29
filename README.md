# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![exp2 theory](https://github.com/user-attachments/assets/5be6f815-1555-41ed-b53e-a21bc3b9446d)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by: DHANVANT KUMAR V
RegisterNumber: 24005057 


**RTL realization**
![exp2](https://github.com/user-attachments/assets/54d8066c-702a-4957-b23f-295d29f87ad0)

**Timing Diagram**
![Waveform result screenshot](https://github.com/user-attachments/assets/532326c1-ec01-4109-b218-d36e11ad30e9)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

