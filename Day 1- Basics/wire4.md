# Day 1 - Wire4

## 🎯 Problem Description
Create a module with 3 inputs and 4 outputs that behaves like wires that makes these connections:  
a -> w  
b -> x  
b -> y  
c -> z

<img width="800" height="276" alt="image" src="https://github.com/user-attachments/assets/a044c90f-ac54-4df4-8f07-b018c460d782" />

## 📄 Verilog Code
```verilog
// use concatenation operator instead of multiple assign statement
module top_module( 
    input a,b,c,
    output w,x,y,z );
    assign {w,x,y,z}= {a,b,b,c};
endmodule


