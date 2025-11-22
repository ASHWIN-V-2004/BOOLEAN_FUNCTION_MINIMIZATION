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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming./*
```
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F  
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```
Developed by:ASHWIN V RegisterNumber:25015303


**RTL realization**

**Output:**
<img width="1221" height="247" alt="Screenshot 2025-11-19 130501" src="https://github.com/user-attachments/assets/90c3f29d-5975-4de6-aaaa-610a8229f2b8" />

**RTL**

<img width="1021" height="625" alt="Screenshot 2025-11-19 130539" src="https://github.com/user-attachments/assets/5ec7388e-89f6-4789-9469-e1fa1291b49d" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

