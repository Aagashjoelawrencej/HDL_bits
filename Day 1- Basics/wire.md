# Day 1 – Wire

## 🎯 Problem Description
Create a module with one input and one output that behaves like a wire.

## 📄 Verilog Code
```verilog
//Use assign keyword to connect out to in (continuous assignment)
module top_module( input in, output out );
    assign out=in;
endmodule
