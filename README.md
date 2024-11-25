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

![Screenshot (54)](https://github.com/user-attachments/assets/d5bc7c1a-ced4-48e5-bdd2-204733389f85)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module exp2(a,b,f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nor(f_nor,a,b);
nand(f_nand,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule


Developed by: AKSHAYA V A

RegisterNumber: 24900449


**Output:**

**RTL**

![Screenshot (54)](https://github.com/user-attachments/assets/d5bc7c1a-ced4-48e5-bdd2-204733389f85)


**Timing Diagram**

![Screenshot (22)](https://github.com/user-attachments/assets/3ddf4937-a16e-4292-a5f7-24a94c148ef1)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

