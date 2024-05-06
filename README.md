# Multiplexer4to1
# Truth Table
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f8ea8610-f6fc-4de3-a68a-5a9a4cfcd673)

program
```
module mux(a,b,c,d,s0,s1,y);
input a,b,c,d,s0,s1;
output y;
assign y=s1 ?(s0?d:c):(s0?b:a);
endmodule
```
output

![image](https://github.com/lavakumaryadhava/Multiplexer4to1/assets/162088994/3c446d84-08ef-46a4-b2b2-f14ecdeb7781)

result 
Thus, Multiplexer4to1 using Vivado 2023.2 is simulated and synthesised.
