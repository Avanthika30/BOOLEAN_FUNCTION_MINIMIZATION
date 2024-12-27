# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions
**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
1)```module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule```

2)```module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule```


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Avanthika.B  RegisterNumber:212224040039*/


**RTL realization**
1)
![ep 2](https://github.com/user-attachments/assets/619c7484-9c24-447d-9fa6-d3f76c202811)
2)
![image](https://github.com/user-attachments/assets/4a5ff488-aa8d-4042-95a9-ba04f0aed559)

**Output:**
1)
![ep 2 1](https://github.com/user-attachments/assets/540b8da6-d73d-4e96-8360-40c7b36e9796)
2)
![image](https://github.com/user-attachments/assets/124ff0de-4289-4f2d-ae8b-37acc94abe04)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

