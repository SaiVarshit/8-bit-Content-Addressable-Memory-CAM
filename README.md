# 8-bit-CAM-Content-Addressable-Memory
Content addressable memory (CAM) is a data storage device, that stores memory in cells. When any aspect of the memory is entered, the CAM compares the input with all the stored data. It is a high-speed technology. In CAM memories are not arranged in chronological order and are not packed in isolated modules.

The project focuses on the design and performance analysis of a simple 8-bit CAM circuit. The circuit is simulated using DSCH2 software. The 8-bit CAM can be implemented with either NAND gates or transmission gates (CMOS).

The aim of the project is to get familiar with memories and the DSCH software.

The DSCH program is a logic editor and simulator used to validate the architecture of logic circuits before beginning microelectronics design.The Dsch can generate the Verilog code file.

# CAM
CAM is used in very high-speed searching applications. It is also called associative memory, associative storage, or associative array.

Features of CAM:

It is used in the database management system.
It is also called Associative memory.
CAM is expensive than RAM.
CAM is suitable for parallel search.
It returns the list of data word address that was located.

The basic cell diagram of a CAM consists of

![Screenshot 2024-06-29 142532](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/b3ff8246-55bb-42d3-befe-bf4341b118f0)

# DSCH
We can generate 1 bit CAM cell either using NAND,NOR or Transmission Gates.
First I have generated a 1 bit CAM using NAND gates.
![1 bit CAM using NAND ](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/4dbb182c-d083-427c-a9f5-f975a7a9bc48)

Circuit diagram
![circuit diagram of 1 bit CAM](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/c708d85b-872f-474e-82f6-8226af33806f)

Simulation Output
![simulation output of 1 bit CAM](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/e4f8bca1-af6b-4793-8778-f1a39ea586de)

Then I have constructed the 8 bit CAM by instantiating 1 bit CAM. 
![8 bit CAM using 1 bit CAM](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/bba8ec5a-8aa7-4bae-8747-d4bb3a125224)
![8 bit circuit diagram](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/7de92cc6-561f-42e0-b925-58cc8dfb3fb3)

Simulation Output.
![Simulation output](https://github.com/SaiVarshit/8-bit-Content-Addressable-Memory-CAM/assets/171639583/587c71c2-4bc5-4479-9c3a-0156b0e04fd3)
