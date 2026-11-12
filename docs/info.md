<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The project is a 2 input AND gate which Inputs A and B come in on ui[2] and ui[3] and output goes high to uo[3] when both A and B are high.

## How to test

Set ui[2] and ui[3] through the four combinations (00, 01, 10, 11). uo[3] should be high only for 11. Connect an LED to uo[3] to see the result.

## External hardware

An LED with a series resistor on uo[3] (optional)
