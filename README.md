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
Program to implement the given logic function and to verify its operations in quartus
 using Verilog programming.
 i)
 module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
 ii)
 module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y));
 endmodule



**RTL realization**
OUTPUT: i)

<img width="954" height="502" alt="Screenshot 2025-11-25 220433" src="https://github.com/user-attachments/assets/c548980e-06c5-43f8-919e-f2a42bfe6d5f" />


ii)

<img width="936" height="496" alt="Screenshot 2025-11-25 220459" src="https://github.com/user-attachments/assets/c728117d-7ee4-44fd-9a2a-49c109b096b8" />




**RTL**
Timing Diagram i)
<img width="934" height="494" alt="Screenshot 2025-11-25 231014" src="https://github.com/user-attachments/assets/aa446e86-7473-4661-a695-93c581fd1320" />


ii)
<img width="935" height="491" alt="Screenshot 2025-11-25 231030" src="https://github.com/user-attachments/assets/2231714b-be5d-4395-ab76-8af7a3245d1f" />



**Result:**
Thus the given logic functions are implemented using and their operations are verified
 using Verilog programming

