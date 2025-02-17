# Leakage Power Reduction Techniques in Deep Submicron Technologies.

<div style="text-align: justify;">
  
The **Sleepy Keeper Technique (SKT) is a low-power VLSI design** method that reduces leakage power while retaining circuit state. It uses sleep transistors (PMOS and NMOS) to disconnect the circuit from power (Vdd) and ground (GND) during standby mode, minimizing leakage current. A small keeper transistor is placed parallel to the sleep transistor to maintain a weak connection, ensuring that logic states are preserved even when the circuit is in sleep mode. This technique provides better leakage reduction than the Sleepy Stack method while avoiding data loss. However, it increases circuit area due to additional transistors.

</div>

**Softwares Used**
1. Vivado
2. DSCH (Digital Schematic)
3. Microwind

# 1. Sleepy Keeper Concept NAND Logic

<div style="text-align: justify;">
  
**A NAND gate (NOT AND)** is a fundamental digital logic gate that produces a LOW (0) output only when all its inputs are HIGH (1); otherwise, it outputs HIGH (1). It is considered a universal gate because it can be used to implement any other logic gate, including AND, OR, and NOT gates.

</div>

**Schematic in DSCH**

![image](https://github.com/user-attachments/assets/ae85c362-9497-4478-b4bd-557f4740dcf9)

**Layout Design in Microwind**
Sleepy Keeper concept NAND Transistor Level Layout diagram designed in microwind software. 

![image](https://github.com/user-attachments/assets/36cfd53f-7d45-49f5-9f0e-f649d148351f)

**Logic Timing Diagram**

![image](https://github.com/user-attachments/assets/0a97235e-96cd-4ebd-a51d-aa31335c1dcb)
![image](https://github.com/user-attachments/assets/8699668e-b214-4962-99c1-0b4ac99f813f)

# 2. Sleepy Keeper Half Adder Circuit

<div style="text-align: justify;">
  
A **Half Adder** is a fundamental digital circuit used for adding two single-bit binary numbers. It has two inputs and produces two outputs: Sum and Carry. The Sum output represents the result of the addition, while the Carry output indicates if there is a carry to the next higher bit. Since a half adder does not account for carry input from a previous stage, it is mainly used in basic arithmetic operations where carry propagation is not required.

</div>

**Schematic in DSCH**

![image](https://github.com/user-attachments/assets/2b9d3541-801b-45c1-a052-2abc735aa094)

**Layout Design**

![image](https://github.com/user-attachments/assets/e64ac179-9041-461a-b8c3-2d6b93d33d9a)

**Logic Timing Diagram**

![image](https://github.com/user-attachments/assets/4ab86d64-2aea-4455-bb68-5e929c6691c9)

# 3. Sleepy Keeper NOR Transistor Level Circuit

<div style="text-align: justify;">
  
A NOR gate (NOT OR) is a digital logic gate that produces a HIGH (1) output only when all its inputs are LOW (0); otherwise, it outputs LOW (0). It is a universal gate, meaning it can be used to construct any other logic gate, including AND, OR, and NOT. NOR gates are commonly used in digital circuits for logic minimization and designing combinational and sequential circuits.

</div>

**Schematic in DSCH**

![image](https://github.com/user-attachments/assets/ea7467fd-725f-4f69-8feb-537fa9e7bcc8)

**Layout Design**

![image](https://github.com/user-attachments/assets/93fe4ab4-8e33-44b2-a47d-729a1bd6a1f2)

**Logic Timing Diagram**

![image](https://github.com/user-attachments/assets/582572bf-4b15-4bdb-8f60-2c2ec0e6ac53)






