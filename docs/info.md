<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Explain how your project works

The 1-bit ALU implements 4 different operations: AND, NOT, OR, ADD.

## How to test

Explain how to use your project

Set the operating mode via the DIP switches with F0 and F1.
                 
                 Next, set the input with A and B and enable both signals with ENA=1 and ENB=1.
                 If you choose to invert A, set INVA to 1, otherwise to 0.
                 For F0=1 and F1=1 you can set CIN as additional input for the ADD operation.
                 
                 The 7-segment display shows either a `0` or a `1` depending on the output.
                 If the ADD operation is selected, the dot of the 7-segment display represents the COUT.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
