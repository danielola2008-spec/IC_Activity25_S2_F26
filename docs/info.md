<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

It takes two input bits (A and B) plus a carry-in (Cin) and outputs their sum: S = A ⊕ B ⊕ Cin, which is 1 when an odd number of the inputs are 1, and Cout = AB + Cin(A ⊕ B), which is 1 when at least two of the inputs are 1

## How to test

You test a full adder by going through all 8 combinations of A, B and Cin and checking both outputs against the truth table.

## External hardware

3 slide switches (inputs A, B, Cin)
2 LEDs (outputs S, Cout)
2 resistors, 220 Ω (current limiting for the LEDs)
2 XOR gates
2 AND gates
1 OR gate
Breadboard, 5 V power, GND, jumper wires
