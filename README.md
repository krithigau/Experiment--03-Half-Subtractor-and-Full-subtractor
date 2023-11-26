# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure

Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led
glows.
## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: U KRITHIGA
RegisterNumber: 23006499 
*/

## Code:
HALF SUBTRACTOR
![HS CODE](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/c208d5c7-2226-4428-a00c-d7157f901a1f)

FULL SUBTRACTOR
![FS code](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/f6b31e70-90fc-4402-a25f-4fcb3a12e590)

## Truthtable
HALF SUBTRACTOR
![TT for HS](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/f392844c-88b7-4eed-8a0d-0596ca6f56c0)

FULL SUBTRACTOR
![TT FOR FS](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/666cc306-1e83-4ed1-9896-90ecb94572f5)

##  RTL realization
HALF SUBTRACTOR
![HS RTL](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/49cdaec2-0170-4ef3-b9e7-fd01120400f1)

FULL SUBTRACTOR
![RTL for FS](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/5d040e9d-13d6-4c0d-a4be-afcf975f69df)

## Timing diagram 
HALF SUBTRACTOR
![Timeline for HS (2)](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/423f02fe-e3de-4fd7-8139-4fc1e1321a68)

FULL SUBTRACTOR
![Timeline for FS](https://github.com/krithigau/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319401/117423c6-5683-48fe-bc6d-3a2e09ce9283)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
