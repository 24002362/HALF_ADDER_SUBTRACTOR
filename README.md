### NAME: HARIPRIYA M
### REG NO: 24002362
### DATE: 17.10.2024
# EXPERIMENT 3: Implementation of Half Adder and Half Subtractor circuit


## AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

## Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

## Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## Program:
![Screenshot 2024-11-14 224057](https://github.com/user-attachments/assets/5896674e-c031-4b33-8886-a41921836be0)


## Logic symbol and Truth Table

#### HALF ADDER:
![Screenshot 2024-11-14 230920](https://github.com/user-attachments/assets/0111021d-27e3-4f5e-8e5c-5ef9e971aec4)

#### HALF SUBTRACTOR:
![Screenshot 2024-11-14 231222](https://github.com/user-attachments/assets/53703685-81c4-441a-942c-63e8eb30a286)


## RTL Output
![Screenshot 2024-11-14 224128](https://github.com/user-attachments/assets/58ca1a53-c51a-4f69-bf11-3b786dd6f083)


## Output/TIMING Waveform
#### HALF ADDER:
![Screenshot 2024-11-18 100355](https://github.com/user-attachments/assets/cdeabeae-421c-4ca7-ae22-ff9729a76383)


#### HALF SUBTRACTOR:
![Screenshot 2024-11-18 100754](https://github.com/user-attachments/assets/020851e1-7702-40e4-ba95-32a4b41cc8cc)




## Result:
Thus the Half adder and Half subtractor circuits are designed and the truth tables are verified using quartus software.


