# Leakage Power Reduction Techniques in Deep Submicron Technologies

The **Sleepy Keeper Technique (SKT) is a low-power VLSI design** method that reduces leakage power while retaining circuit state. It uses sleep transistors (PMOS and NMOS) to disconnect the circuit from power (Vdd) and ground (GND) during standby mode, minimizing leakage current. A small keeper transistor is placed parallel to the sleep transistor to maintain a weak connection, ensuring that logic states are preserved even when the circuit is in sleep mode. This technique provides better leakage reduction than the Sleepy Stack method while avoiding data loss. However, it increases circuit area due to additional transistors.

**Softwares Used**
1. Vivado
2. DSCH (Digital Schematic)
3. Microwind

# Sleepy Keeper Concept

**Sleepy Keeper Concept NAND Logic**

![image](https://github.com/user-attachments/assets/81305142-b630-4e00-a797-2e92ed4dc470)

**Layout Design**
Sleepy Keeper concept NAND Transistor Level Layout diagram designed in microwind software. 

![image](https://github.com/user-attachments/assets/36cfd53f-7d45-49f5-9f0e-f649d148351f)

**Logic timing diagram**

![image](https://github.com/user-attachments/assets/0a97235e-96cd-4ebd-a51d-aa31335c1dcb)
![image](https://github.com/user-attachments/assets/8699668e-b214-4962-99c1-0b4ac99f813f)

**Sleepy Keeper concept half adder circuit**

![image](https://github.com/user-attachments/assets/2b9d3541-801b-45c1-a052-2abc735aa094)

**Layout Design**

![image](https://github.com/user-attachments/assets/e64ac179-9041-461a-b8c3-2d6b93d33d9a)

**Logic timing diagram**

![image](https://github.com/user-attachments/assets/4ab86d64-2aea-4455-bb68-5e929c6691c9)

**Sleepy Keeper concept NOR Transistor level circuit**

![image](https://github.com/user-attachments/assets/ea7467fd-725f-4f69-8feb-537fa9e7bcc8)

**Layout Design**

![image](https://github.com/user-attachments/assets/93fe4ab4-8e33-44b2-a47d-729a1bd6a1f2)

**Logic timing diagram**

![image](https://github.com/user-attachments/assets/582572bf-4b15-4bdb-8f60-2c2ec0e6ac53)






