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

module exp2(a,b,c,d,f1,w,x,y,z,f2);

input a,b,c,d,w,x,y,z;

output f1,f2;

assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));

assign f2=((~y&z)|(x&y)|(w&y));

endmodule 


Developed by:MIRDULA D   RegisterNumber: 25014905


**RTL realization**

<img width="1025" height="685" alt="image" src="https://github.com/user-attachments/assets/b428c886-dd54-4b53-9643-0f480f555c69" />

**Output:**

<img width="1032" height="522" alt="image" src="https://github.com/user-attachments/assets/041ad250-ba0c-4aba-a997-52b0f22b2ca7" />

**RTL**

<img width="1034" height="642" alt="image" src="https://github.com/user-attachments/assets/685c9845-7c2c-448f-854b-f20794c76e5f" />

**Timing Diagram**

<img width="1041" height="819" alt="image" src="https://github.com/user-attachments/assets/75597d22-44b9-4a4b-b129-995eddabfd10" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

