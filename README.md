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

/*module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Lavanya.A RegisterNumber:25007878


**RTL realization**
<img width="1915" height="1074" alt="Screenshot 2025-11-17 140234" src="https://github.com/user-attachments/assets/2960ff27-03c6-4c18-b4e2-9b8eade14f78" />
<img width="1916" height="1068" alt="Screenshot 2025-11-17 140817" src="https://github.com/user-attachments/assets/a4b5a653-887f-445b-b917-fe90877dd56b" />



**Output:**




**RTL**

**Timing Diagram**
<img width="1915" height="1075" alt="Screenshot 2025-11-17 140410" src="https://github.com/user-attachments/assets/7a9cfa8e-fafc-4312-a94d-ca0ce4d78bd4" />
<img width="1909" height="1070" alt="Screenshot 2025-11-17 141031" src="https://github.com/user-attachments/assets/f100bfc1-d5ca-4fb7-b7f2-19a793d25121" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

