- `EDA Playground` gives engineers immediate hands-on exposure to simulating and synthesizing SystemVerilog, Verilog, VHDL, C++/SystemC, and other HDLs. All you need is a web browser.
[EDA playground](https://www.edaplayground.com)


- [Intro to verilog](https://web.mit.edu/6.111/www/f2017/handouts/L03_4.pdf)
- FPGA stands for “Field Programmable Gate Array“. As you may already know, FPGA essentially is a huge array of gates that can be programmed and reconfigured any time anywhere. “Huge array of gates” is an oversimplified description of FPGA. FPGA is indeed much more complex than a simple array of gates. Some FPGAs have built-in hard blocks such as Memory controllers, high-speed communication interfaces, PCIe Endpoints, etc. But the point is, there are a lot of gates inside the FPGA which can be arbitrarily connected together to make a circuit of your choice. 

- Implementing a solution on FPGA includes building the design using one of the design entry methods such as schematics or HDL code such as Verilog or VHDL
- Register Transfer Logic or Register Transfer Language, they all mean the same in the context of hardware designing. RTL is a higher-level abstraction for your digital hardware design and comes somewhere between strictly behavioral modeling on one end and purely gate-level structural modeling on other ends.
- Once the RTL design is ready, it is easier to convert it into actual HDL code using languages such as Verilog, VHDL, SystemVerilog, or any other hardware description language.
- FPGAs are much much more than just a bunch of gates. While it is possible to build logic circuits of any complexity simply by arranging and connecting logic gates, it is just not practical and efficient. So we need a way to express the logic in some easy to use format that can be converted to an array of gates eventually. Two popular ways to accomplish this are schematic entry and HDLs (Hardware Description Language). Before HDLs were popular, engineers used to design everything with schematics. Schematics are wonderfully easy for small designs but are painfully unmanageable for a large design (think about Intel engineers drawing schematics for Pentium, which has millions of gates! it is unacceptably complex).
- Verilog is a Hardware Description Language (HDL) which can be used to describe digital circuits in a textual manner. We will write our design for FPGA using Verilog (as if you write microcontroller programs in C and Assembly)
- this is the weak point of microprocessors/microcontrollers. They can do only one thing at a time, one and only one thing (of course I’m talking about single core devices!). But unlike microprocessors, digital circuits (FPGAs, CPLDs, and ASICs) can do many things at the same time.


## LIST OF EXPERIMENTS



1) Verification of Basic gates in behavioural, structural and gate-level modelling.

2) Verification of Half Adder and Half Subtractor, Full Adder & Full Subtractor.

3) Design and verification of 4-bit Binary Adder and Subtractor.

4) Design and verification of 3×8 Decoder and 8×3 Encoder.

5) Design and verification of 4×1 MUX and 1×4 DeMUX.

6) Design and verification of 4-bit Magnitude Comparator.

7) Verification of Latches and Flip-Flops.

8) Design and verification of 4-bit Shift Registers.

9) Design and verification of 4-bit asynchronous counter.

10) Design and verification of 4-bit Synchronous counter.

11) Design and verification of 4-bit Ring and Johnson counter.


