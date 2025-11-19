# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.
<img width="591" height="732" alt="image" src="https://github.com/user-attachments/assets/a4ea2989-6ac7-4af8-b2aa-386299ef2961" />


 Developed by: MARLIYA BANU B 
RegisterNumber: 25004270
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**
<img width="575" height="801" alt="image" src="https://github.com/user-attachments/assets/9a8eca82-3fab-4637-bf21-c1a3871cc4c6" />


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
<img width="820" height="467" alt="image" src="https://github.com/user-attachments/assets/1b9c7034-7e5a-4efa-95ec-3a3040d53f43" />

**RESULTS**
Thus 4-BIT-RIPPLE-COUNTER is verified successfully.
