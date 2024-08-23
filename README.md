# EX-01 EXECUTION OF LOGIC GATES USING PLC LADDER PROGRAM
### NAME: KAVIYA SHREE S
### REG.NO: 212222110018
 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.

# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

## Basic Logic Gates:
### AND Gate:</br>
Function: Outputs HIGH only when all inputs are HIGH.</br>
Ladder Logic: Represented by two or more normally open contacts in series.</br>

### OR Gate:</br>
Function: Outputs HIGH when at least one input is HIGH.</br>
Ladder Logic: Represented by two or more normally open contacts in parallel.</br>

### NOT Gate:</br>
Function: Outputs the inverse of the input signal.</br>
Ladder Logic: Represented by a normally closed contact.</br>

### NAND Gate:</br>
Function: Outputs LOW only when all inputs are HIGH.</br>
Ladder Logic: An AND gate followed by a NOT gate.</br>

### NOR Gate:</br>
Function: Outputs LOW when at least one input is HIGH.</br>
Ladder Logic: An OR gate followed by a NOT gate.</br>

### XOR Gate:</br>
Function: Outputs HIGH when an odd number of inputs are HIGH.</br>
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.</br>

# Truth Tables:
### AND GATE:
![image](https://github.com/user-attachments/assets/8e49ef57-503e-41ee-a950-21ac8b4e6908)

### OR GATE:
![image](https://github.com/user-attachments/assets/aaf7b0db-8611-4e10-96a9-7b65dbd07e5b)

### NOT GATE:
![image](https://github.com/user-attachments/assets/b7f525d0-b8c5-469f-ac20-16cf47331959)

### NAND GATE:
![image](https://github.com/user-attachments/assets/fb0c5543-7493-47ec-bda9-606bf92b7a5a)

### NOR GATE:
 ![image](https://github.com/user-attachments/assets/4799000e-34ea-42ef-8046-5214184bf6b5)

# Procedure:
#### Setup the PLC Programming Environment:
Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.

#### Create Ladder Logic Programs:
For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.

#### Simulate the Ladder Logic:
Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.

## Download and Execute:
If available, download the ladder logic program to the PLC and run it.</br>
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.</br>
Output of Simulation:</br>
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:</br>
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.</br>
OR Gate: The output should light up when any one or both inputs are HIGH.</br>
NOT Gate: The output should be the inverse of the input state.</br>
NAND Gate: The output should be HIGH except when both inputs are HIGH.</br>
NOR Gate: The output should be HIGH only when both inputs are LOW.</br>
XOR Gate: The output should light up when exactly one input is HIGH.</br>

## Procedure:
### Setup the PLC Programming Environment:
Connect the PLC to the computer system and launch the PLC programming software.</br>
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.</br>
Create Ladder Logic Programs:</br>
For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.</br>
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.</br>
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.</br>
Simulate the Ladder Logic:</br>
Simulate the ladder logic programs in the PLC software.</br>
Toggle the input states and observe the output corresponding to each gate’s truth table.</br>

# SIMULATION RESULTS 
### AND GATE:
![image](https://github.com/user-attachments/assets/2f6cbcb8-732d-4f57-b88c-6417a8a4f82c)

### OR GATE:
![image](https://github.com/user-attachments/assets/ba504b79-a173-4f03-b1c1-0303a5b3e03a)

### NOT GATE:
![image](https://github.com/user-attachments/assets/6732a4b3-b79f-4976-ac04-ec5650af37ec)

### NAND GATE:
![image](https://github.com/user-attachments/assets/16f56012-8cc7-4107-bca1-02530c986d67)

### NOR GATE:
![image](https://github.com/user-attachments/assets/6ea8863d-67f8-4bf4-bf8d-4200bac9847d)

## Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
