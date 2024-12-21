# NAME : RABI BASKAR PRABURAJAN 
# REG NO : 24001812
# EXPERIMENT 10 : SERIAL IN SERIAL OUT SHIFTREGISTER

## AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

## SOFTWARE REQUIRED:

Quartus prime

## THEORY

## SISO shift Register

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

## PROCEDURE :


## PROGRAM :
![EXP 10 DE PROGRAM](https://github.com/user-attachments/assets/6243434b-c088-413c-b2f3-c18703dd5c5d)



## RTL LOGIC FOR SISO Shift Register :
![image](https://github.com/user-attachments/assets/91a5adb0-b47a-4040-9681-d5ddff499c8e)



## TIMING DIGRAMS FOR SISO Shift Register :
![image](https://github.com/user-attachments/assets/36befe5a-fa53-45ba-a502-df84ead4c2f2)



## RESULT :
 SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
