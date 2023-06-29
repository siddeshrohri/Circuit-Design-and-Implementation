# 2-Bit Circuit Design and Implementation

This project involves designing and implementing a circuit in HDL (Hardware Description Language) that takes two 2-bit numbers as input and produces a 3-bit output. The circuit has 6 inputs (f1, f0, A, B, C, D) and 3 outputs (E, F, G). The function of the circuit is determined by the values of f1 and f0.

Assignment Tasks

Task 1: Logic Circuit Implementation

Implement the logic circuit for each output in separate HDL files.
Test each logic circuit to confirm it produces the required output.
The input/output names in the logic circuit files must match those in the truth table.

Task 2: Combined Circuits for Each Truth Table

Combine the circuits for the outputs from Task 1 into one HDL file for each truth table.
Test each combined circuit to ensure it produces the required output.
Name the combined circuits as follows: FZero, FOne, FTwo, FThree.

Task 3: Combined Circuit with All Inputs

Combine all four circuits from Task 2 into one circuit.
This circuit should take all six inputs and produce the correct output based on f1 and f0.
Test the FALL circuit using FALL.tst, but additional tests may be created before submission.

Task 4: Sequence of Operations

Adapt the circuit from Task 3 to combine a sequence of operations based on different f1 and f0 values.
Enable the outputs Ft and Gt to be used as the next inputs for Ct+1 and Dt+1.
Add a new input (Load) that, when set to 1, allows loading inputs to Ct and Dt at the start and during the sequence if required.
This adaptation should support expressions such as X+Y+Z or X-Y, where X, Y, and Z are all 2-bit binary numbers.
Test the FSEQ chip using FSEQ.tst, but additional tests may be created before submission.
