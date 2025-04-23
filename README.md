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
![image](https://github.com/user-attachments/assets/7e54ca98-9b70-4864-a919-0bb3269af561)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
module exp2a(a,b,c,d,F1);
intput a,b,c,d;
output F1;
assign F1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule



module exp2b(w,x,y,z,F2)
intput w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: Rithanya D
RegisterNumber: 212224050038


**RTL realization**
![image](https://github.com/user-attachments/assets/944e008e-c86e-4330-ba3c-6a6f78226746)
![image](https://github.com/user-attachments/assets/53101508-5193-48d7-874c-968230529bb8)



**RTL Timing Diagram**
![image](https://github.com/user-attachments/assets/f948dd7c-607e-4238-9d7a-5a1d96478158)
![image](https://github.com/user-attachments/assets/1af8c08d-d0fa-48b5-b229-803a02f40e6c)




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

