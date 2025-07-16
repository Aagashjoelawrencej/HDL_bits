# Day 1 – Wire

## 🎯 Problem Description
Create a module with one input and one output that behaves like a wire.

## 📄 Verilog Code
```verilog
module mux2to1(input a, input b, input sel, output y);
    assign y = sel ? b : a;
endmodule

