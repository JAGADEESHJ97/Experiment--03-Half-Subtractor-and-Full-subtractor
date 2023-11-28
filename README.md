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
Developed by: 
RegisterNumber:  
*/

## Output:
## HALF SUBTRACTOR
![hal sub pro](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/e972dff4-3af7-4dab-a0d7-2d2ced7ba94b)

## FULL SUBTRACTOR
![ful sub pro](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/b232d4ea-d933-4d7d-a8f7-0506fabc5f4f)

## Truthtable

## HALF SUBTRACTOR
![TT SUB HAL](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/ce67d561-6f69-4db6-817b-580cdce622d2)

## FULL SUBTRACTOR
![TT SUB FULL](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/4d7c42d0-0ac5-4b69-b604-c63b2069c6e8)

##  RTL realization

## HALF SUBTRACTOR
![RTL SUB HAL](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/c2cd6ea4-49eb-44be-a4d1-a93655c1d967)

## FULL SUBTRACTOR
![RTL FULL SUB](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/64f793b4-8428-4537-a098-3082bd14fa3e)

## Timing diagram 

## HALF SUBTRACTOR
![TIME SUB HAL](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/74d456e7-bca0-48e9-ac7d-89c7c6372dfa)

## FULL SUBTRACTOR
![TIME SUB FULL](https://github.com/JAGADEESHJ97/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152129419/66e09e21-cb1a-4227-8480-33861d1c21f5)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
