# Notgate

## 🎯 Problem Description
Create a module that implements a NOT gate. 

<img width="575" height="281" alt="image" src="https://github.com/user-attachments/assets/5a3bfade-fec9-4e27-a9fd-23da1114f7db" />


## 📄 Verilog Code
```verilog
// ~ is bitwise not operator and ! is logical not operator
module top_module( input in, output out );
    assign out= ~in;
endmodule
