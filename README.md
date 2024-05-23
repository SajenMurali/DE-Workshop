# DE-Workshop
### AIM : 
To Simulate verilog HDL for 4 bit Ripple Carry Adder using Quartus II 
### Software Required : 
Quartus II

### Deeveloped By : SAJEN MURALI
### Register Number : 212223220089
### PROGRAM :
```
module RippleCarryAdder(
    input [3:0] A,
    input [3:0] B,
    input Cin,
    output [3:0] Sum,
    output Cout
);

wire [3:0] Carry;
assign Carry[0] = Cin;
assign {Cout, Sum} = A + B + Carry;

endmodule

```
## OUTPUT :
### RTL Viewer :

![image](https://github.com/Madhavareddy09/DE-Workshop/assets/145742470/654b0618-e120-4bff-8894-a9105969f33b)

### Simulation : 


### RESULT :
Thus the Simulation of verilog HDL for 4 bit Ripple Carry Adder using Quartus II is executed Successfully.
