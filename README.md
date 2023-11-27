# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder:
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder:
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure:
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: ASHWINA K N
RegisterNumber: 23001424
##CODE:
##HALF ADDER:
![Exp3 ha code](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/618b72db-48c2-482c-8423-369b407ad3dd)

##FULL ADDER:
![Exp3 fa code](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/6ae1e22c-21cd-4bae-8766-42e6a6e2c1a9)

##TRUTH TABLE:
##HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/2ba0dbf3-588d-453a-adc3-f10def94f3e7)

##FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/d1c16b47-b7de-4426-bb50-a45d063307c3)

### RTL:
### TIMING DIAGRAM:
##HALF ADDER:
![Exp3 ha RTL diagram](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/fba624fb-b428-4c71-91a1-247835d87772)

##FULL ADDER:
![Exp3 fa RTL diagram](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/da5520b8-2122-4b04-8541-db4930b0f380)

### Output:
##HALF ADDER:
![exp3 ha wave](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/8d439cdb-ec57-4933-9927-314b46c56af8)

##FULL ADDER:
![exp 3 fa wave](https://github.com/Ashwinakn/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152128332/970914fc-9540-46e2-b1c2-d6aab05ce341)


### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming
