# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**

Inputs:
T: Toggle input.
clk: Clock signal.
reset (optional): To initialize or reset the output.

Output:
Q: The current state (output).

Behavior:
On the rising edge of the clock:
If T = 1: The output toggles (Q = ~Q).
If T = 0: The output remains unchanged.
If a reset is present, the output resets to 0.

**PROGRAM**

DEVELOPED BY:RAJASHRI I , REGISTER NUMBER :24900207

![DE ex9 code](https://github.com/user-attachments/assets/917e98b9-dfd2-45d6-9ed2-7de94e15118e)


**RTL LOGIC FOR FLIPFLOPS**

![DE ex9 diagram](https://github.com/user-attachments/assets/82e48a51-cd4f-4356-9a2a-9654878aa220)


**TIMING DIGRAMS FOR FLIP FLOPS**

![DE ex9 wave](https://github.com/user-attachments/assets/3a7ea28e-e5cd-42ef-8d81-c965d11ba6a1)


**RESULTS**
The implementation  T flipflop using verilog and validating their functionality using their functional tables

