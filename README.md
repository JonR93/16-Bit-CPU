REPORT 1:
Using the architecture and the instruction format for the 16-bit CPU descibed in the semester project design a simpilfied single-cycle datapath capable of executing all R-type instructions and the addi instruction. Major components: Instruction memory, ALU, and Register File. Use template files: ALU4.vl (extend it to 16 bit) and regfile.vl (change the D flip-flops with 16-bit registers and redesign mux4x1 using gate-level modeling and extend it to 16-bit data). See the behavioral implementation mips-r-type+addi.vl. For testing use the test program test-r-addi.asm and adjust it to the 16-bit version of MIPS following the requirements given in section "Testing". 

REPORT 2:
Complete single-cycle datapath. Implement all instructions and run a complete test program as explained in section "Testing". See the behavioral model of MIPS mips-simple.vl for the implementation of the data memory and branching logic. Use the test program from mips-simple.vl extended with the bne instruction and run it with different data to simulate both branch decisions (taken and not taken). Include in the report: A top-level diagram of the datapath, Verilog source files and test results.

REPORT 3:
3-stage pipelined datapath for addi and R-type instructions. Use the 3-stage behavioural model mips-pipe3.vl and make the necessary changes. For testing use the test program from mips-pipe3.vl and adjust it to the project 16-bit architecture. Include in the report: A top-level diagram of the datapath, Verilog source files and test results. The test results should include simulations with and without nop's that demonstarte the pipeline hazards.

FINAL:
Implement the final version of the complete pipelined datapath. Use the behavioural model mips-pipe.vl and make the necessary changes according to the Semester Project specifications. Write a general description of the machine and short description of each major component, include the Verilog code with comments and results from running the Verilog program simulating the MIPS test program (see the "Testing" section in Semester Project).
