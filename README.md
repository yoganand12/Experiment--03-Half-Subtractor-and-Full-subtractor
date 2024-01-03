## Ex:03 Half Subtractor and Full subtractor
## Implementation of Half subtractor and Full subtractor circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.
## Equipments Required:
## Hardware 
PCs, Cyclone II , USB flasher
## Software 
Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.
## Half Subtractor Full Subtractor
## Half Subtractor:
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)
Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y
## Full Subtractor:
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)
Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin
## Program:

## Half Subtractor:

![Screenshot 2024-01-03 213803](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/4429192a-f781-4f7a-9869-17dd72ab52d8)


## Full Subtractor:

![Screenshot 2024-01-03 213814](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/5ac25495-c9ab-47d4-a8e3-d79165759221)

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
## Truthtable:

## Half Subtractor:

![Screenshot 2024-01-03 213824](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/3116a59b-7faf-4598-bb13-d4918673b939)


## Full Subtractor:

![Screenshot 2024-01-03 213832](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/b7c20b3f-648a-4696-82c8-698ef1a9626f)

##  RTL realization:

## Half Subtractor:

![Screenshot 2024-01-03 213846](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/6895d1c1-a81d-4cfd-aefd-83fa4c28f73c)

## Full Subtractor:

![Screenshot 2024-01-03 213855](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/cfc152cd-b729-4397-a3ad-12d2fd8af865)

## Timing diagram: 

## Half Subtractor:
![Screenshot 2024-01-03 213903](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/f26378c8-58e6-4b64-8e46-16027ba1461f)


## Full Subtractor:
![Screenshot 2024-01-03 213912](https://github.com/yoganand12/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155515519/a0929b80-e6c3-4fff-ba6b-4b985d5e936d)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
