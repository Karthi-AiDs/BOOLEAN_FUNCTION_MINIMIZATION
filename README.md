# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![image](https://github.com/user-attachments/assets/f90925b1-4ec7-4ec5-920b-604055c6c1cb)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

```
module boolean (f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and (f_and,a,b);
or (f_or,a,b);
not (f_not,a);
nor (f_nor,a,b);
nand (f_nand,a,b);
xor (f_xor,a,b);
xnor (f_xnor,a,b);
endmodule
```

Developed by: KARTHIKEYAN D

RegisterNumber: 24000848


**RTL**

![Screenshot 2024-11-22 211513](https://github.com/user-attachments/assets/23d143c3-5d5d-4594-bac7-ead1aee4f2e6)



**Timing Diagram**

![Screenshot (31)](https://github.com/user-attachments/assets/dec67f31-ce92-49a2-93c5-dac82b102866)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

