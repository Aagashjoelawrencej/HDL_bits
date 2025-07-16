# Wire

## 🎯 Problem Description
Create a module with one input and one output that behaves like a wire.

<img width="800" height="324" alt="image" src="https://github.com/user-attachments/assets/1ad8a56c-f1a8-41b8-b482-7d7e2f7c22b5" />

## 📄 Verilog Code
```verilog
//Use assign keyword to connect out to in (continuous assignment)
module top_module( input in, output out );
    assign out=in;
endmodule
