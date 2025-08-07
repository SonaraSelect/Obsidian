
## Sample Project Guide

>What i can suggest is to upskill yourself voluntarily, You will need maximum of 6-8 months of full time dedication before you can easily feth multiple offers on entry level, Here is what i would do in your place...

1. Buy a cheap FPGA development board such as CoraZ7 with Zynq
    
2. Start with the most simplest example design, Understand the RTL code, Synthesise, Implement, Generate bit stream
    
3. Understand what synthesis tool does, how RTL code was translated into a schematic (FFs, LUTs .. etc)
    
4. Analyze the timing reports, How tool reports clocks and how it performs STA (Timing analysis), understand parameters such as slack, setup times, hold times.
    
5. How critical path between two Registers affect timing and how tool analyses these.
    
6. How synthesized netlist is placed and routed inside the FPGA after implementation, Explore concept of floorplanning in implemented design.
    
7. Understand constraints (Physical, Timing, Placement), You dont have to dive deep into these
    
8. Basic understanding of timing constraints such as create_clock, create _generated_clock, create_clock_groups, set_false_path will enable you to quickly grasp timing constraints in complex digital circuits involving multiple clock domains, Input, output to FPGA from external peripheral and how the trace delays on PCB will affect timing of the peripheral or a circuit inside the FPGA, This doesnt have to be too deep, i would guess there are plenty of good tutorials from AMD
    
9. After i am done from step 1 to 8, I would pick a slightly more complex design maybe involving cameras/image/video acquisition, there are plenty examples online related to this & then do repeat steps 1-8 again.
    
10. After step 9, I would go one step further and do something with Ethernet & Petalinux, and then somehow combine my earlier project with Ethernet and do something with PetaLinux, This will boost my skill level to more higher level where experience with Ethernet is often required by companies.
    
11. Its a never ending process, There will never be a shortage of projects one can do even with a tiny board like CoraZ7 but by this time you are equipped with enough skills to be easily offered multiple entry level positions, There are plenty of companies looking for FPGA developers mostly just a right skillset is missing....