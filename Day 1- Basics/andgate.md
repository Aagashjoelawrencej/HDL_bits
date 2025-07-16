# Andgate

## 🎯 Problem Description
Create a module that implements an AND gate.  
<img width="586" height="281" alt="image" src="https://github.com/user-attachments/assets/b42d8ab6-2687-4e32-b29e-1448bc10266f" />  

## 📄 Verilog Code
```verilog
// & is bitwise and operator, && is logical and operator
module top_module( 
    input a, 
    input b, 
    output out );
    assign out= a&b;
endmodule
