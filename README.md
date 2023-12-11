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

![Screenshot 2023-11-26 150019](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/7c46ebbd-1ba8-4484-9c2a-1debe889c039)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 

![Screenshot 2023-11-26 144204](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/a363f4e2-cdb9-4aaf-82dd-49bc386c08ca)

Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
![Screenshot 2023-11-26 143908](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/86a6b008-7d49-4f35-80cb-99f4a045ef27)

![Screenshot 2023-11-26 150550](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/4bfc1ae8-3150-4166-8e74-4563b3e3334a)


Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable
![th](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/d35376bb-5426-4b85-84aa-3ea02326938e)

![th](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/bf8edecd-0ade-4af5-a7a8-97e8a8a6ff89)


##  RTL realization


## Timing diagram 
![Screenshot 2023-11-26 143851](https://github.com/Mohanraj2006/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152195759/0cfe7a77-1ae7-4411-bf76-2a1180890e80)
![Uploading Screenshot 2023-11-26 150532.png…]()

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
