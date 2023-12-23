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

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by: NATARAJ KUMARAN S

RegisterNumber:  23003973

## HALF SUBTRACTOR:
![Screenshot 2023-12-23 113521](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/c672d9d1-76b3-463d-8483-e06d6cff4711)

## FULL SUBTRACTOR:
![Screenshot 2023-12-23 111453](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/42a7d67e-5756-47a2-8b6b-92643f173291)




## Output:
## HALF SUBTRACTOR:
![Screenshot 2023-12-23 121110](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/a5339dd1-097b-44ec-9277-f33e6dadedb3)
## FULL SUBRTRACTOR:
![Screenshot 2023-12-23 111357](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/57dbf7f6-e04a-43c4-af20-7f226fd12e0b)




## Truthtable: 
## HALF SUBTRACTOR:
![Screenshot 2023-12-23 115634](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/8d472a4f-cfc3-4606-8304-3c5affa5f32a)
## FULL SUBTRACTOR:
![Screenshot 2023-12-23 111942](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/d67ffd4f-70af-4f9a-b4e3-4af7899006c1)





##  RTL realization:
## HALF SUBTRACTOR:
![Screenshot 2023-12-23 120307](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/59978d50-c468-4836-b3dd-c7d8ad97d812)
## FULL SUBTRACTOR:
![Screenshot 2023-12-23 111022](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/4ff6742b-620b-49bf-bae6-d2a51ced6f7c)




## Timing diagram :
## HALF SUBTRACTOR:
![Screenshot 2023-12-23 114621](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/cb868e1c-6f31-44d1-992e-22ed486a20a6)

## FULL SUBTRACTOR:
![Screenshot 2023-12-23 111357](https://github.com/nataraj26/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147514615/b4b6805f-9266-418d-8919-3c7399185abb)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
