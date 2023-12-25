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



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Srimathi.M
RegisterNumber:212223050053   
*/
## HS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/d78bda24-7c65-4e73-956c-fdc3cd199f31)

## FS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/94f4c40e-f925-4637-9186-12d3061d3770)

## RTL
## HS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/9e9b8fbd-5833-443f-83d7-0cc3dd8cda70)

## FS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/9fdc9df4-a028-417b-a8b8-15591dcde32b)

## TRUTH TABLE
## HS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/b357d2a7-5b3d-4f25-ba88-dd8fe815916a)

## FS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/521e1699-5494-44ab-8764-9b6ca3036035)

## OUTPUT
## HS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/0baa7c80-b3f0-493c-9290-a6bf5a29c8ad)

## FS
![image](https://github.com/srimathi1602/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153518608/0054f157-c92e-447a-b00d-4c69ccd6eb41)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
