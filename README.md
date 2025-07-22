# 4Bit-Shift-and-Adder-Multiplier

**OBJECTIVE**


Write Verilog code for a 4-bit shift-and-add multiplier.

Verify functionality using a testbench.

Perform synthesis and analyze reports:

Critical path

Maximum delay

Number of cells

Power and area requirement


**DESCRIPTION**

Binary multipliers are used for multiplication of 2 binary numbers and are used mainly in signal processing and also in other computationally intensive applications. Shift and add binary multiplier is a type of sequential multiplier. Sequential multipliers generate the partial products sequentially and add each newly generated partial product to the previously accumulated sum. Shift and add binary multiplier is a type of sequential multiplier.Shift and add multiplier is similar to multiplication done by paper and pencil. This method adds the multiplicand X to itself Y times, where Y denotes the multiplier In the case of binary multiplication, since the digits are 0 and 1, if the multiplier digit is 1, a copy of the multiplicand is placed in the proper positions; if the multiplier digit is 0, a number of 0 digits are placed. The 2n- bit product register (A) is initialized to 0. A 2n-bit multiplicand register with the multiplicand placed in the right half of the register and with 0 in the left half is used. The algorithm starts by loading the multiplicand into the B register, loading the multiplier into the Q register, and initializing the A register to 0. The counter N is initialized to n. The least significant bit of the multiplier register (Q0) determines whether the multiplicand is added to the product register. The left shift of the multiplicand has the effect of shifting the intermediate products to the left and right shift prepares the next bit of the multiplier to examine in the following iteration.


**OUTPUT WAVEFORM**


<img width="529" height="106" alt="Image" src="https://github.com/user-attachments/assets/b0a11871-7f45-4e3c-a002-d2dcae36b5ab" />


**SYNTHESIS RTL SCHEMATIC**


<img width="545" height="376" alt="Image" src="https://github.com/user-attachments/assets/33eb589a-1b89-4864-9355-17b99081caf6" />
