# 8-bit-CAM-Content-Addressable-Memory
Content addressable memory (CAM) is a data storage device, that stores memory in cells. When any aspect of the memory is entered, the CAM compares the input with all the stored data. It is a high-speed technology. In CAM memories are not arranged in chronological order and are not packed in isolated modules.

CAM is used in very high-speed searching applications. It is also called associative memory, associative storage, or associative array.

Features of CAM:

It is used in the database management system.
It is also called Associative memory.
CAM is expensive than RAM.
CAM is suitable for parallel search.
It returns the list of data word address that was located.

The project focuses on the design and performance analysis of a simple 8-bit CAM circuit. The circuit is simulated using DSCH2 software. The 8-bit CAM can be implemented with either NAND gates or transmission gates (CMOS).

The aim of the project is to get familiar with memories and the DSCH software.

The DSCH program is a logic editor and simulator used to validate the architecture of logic circuits before beginning microelectronics design.The Dsch can generate the Verilog code file.

# DSCH
The basic cell diagram of a CAM consists of

First I have generated a 1 bit CAM using NAND gates.
![Screenshot 2024-06-29 084226](https://github.com/Adish30/8-bit-CAM-Content-Addressable-Memory-/assets/114245305/0c2d0e9a-fa1e-454b-ad21-383262545141)
Next, using the above instantiation, 8 bit CAM can be generated.
![Screenshot 2024-06-29 084155](https://github.com/Adish30/8-bit-CAM-Content-Addressable-Memory-/assets/114245305/4b7ddf4b-a356-485d-90c9-d14922d78960)
The simulation output of the circuit.(Glowing of LEDS indicate the BL and SL are same and outut Matched Line is high)
![Screenshot 2024-06-29 085421](https://github.com/Adish30/8-bit-CAM-Content-Addressable-Memory-/assets/114245305/bb60c3c2-b494-41a4-8e76-49a79905f2cb)
