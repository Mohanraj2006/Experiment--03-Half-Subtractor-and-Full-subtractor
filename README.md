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

 
Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 

 
Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
 
 ![Screenshot 2023-12-25 211041](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/df1a7edf-bb0d-433c-8fa0-8e34810839e6)

Write the detailed procedure here 


## Program:
## Half Subtractor
![Screenshot 2023-12-25 211047](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/fee9e4e9-2a41-464e-833f-4114a09a1394)


## Full Subtractor

![Screenshot 2023-12-25 211052](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/853a82a6-682e-4564-9b40-6ea3731e45e6)


/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Mohan raj.C
RegisterNumber:23014008 
*/

## Output:

##  RTL realization
## Half Subtractor
![Screenshot 2023-12-25 211112](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/cca2103a-c254-452b-9cab-e6c0068838dc)


## Full Subtractor

![Screenshot 2023-12-25 211116](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/4e6ca59c-e5f5-40b8-97e7-bb177c34f6e7)

## Truthtable
## Half Subtractor
![Screenshot 2023-12-25 211123](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/e595d88c-da3f-498c-93c2-0608b1683606)


## Full Subtractor

![Screenshot 2023-12-25 211128](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/29ca1f9e-6fa9-4a67-afae-2cc6c5c940e9)


## Timing diagram 

## Half Subtractor

![Screenshot 2023-12-25 211136](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/ac9e02ad-8447-4825-b054-b5bf07ddfc15)


## Full Subtractor

![Screenshot 2023-12-25 211145](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/1bbf4a32-dff7-4396-a839-e6d30ea91abb)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
