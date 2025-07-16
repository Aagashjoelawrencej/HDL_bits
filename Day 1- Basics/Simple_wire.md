# Day 1 – Mux 2-to-1

## 🎯 Problem Description
Design a 2-input multiplexer using assign statement in Verilog.

## 📄 Verilog Code
```verilog
module mux2to1(input a, input b, input sel, output y);
    assign y = sel ? b : a;
endmodule

