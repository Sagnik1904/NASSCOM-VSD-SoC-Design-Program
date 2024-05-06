# NASSCOM-VSD-SoC-Design-Program
Day 1
What is Chip ?
A chip refers to an integrated circuit (IC) or a small wafer of semiconductor material embedded with integrated circuitry. These chips serve as the processing and memory units in modern digital computers. The manufacturing process for chips is extremely precise and typically takes place in a “clean room” to prevent even microscopic contamination, which could render a chip defective. Over time, the number of transistors per chip has doubled approximately every 18 months due to advancements in technology—a phenomenon known as Moore’s law.
<img width="404" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/e0ff1b95-d9ca-4dd4-8617-54aa06c49643">

What Is SoC?
A System on a Chip (SoC) is an integrated circuit that combines many elements of a computer system into a single chip. Here’s a quick breakdown:

<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/f96d3ba2-3810-482e-bd52-0efab13370b2">


Components in an SoC:
1.CPU: An SoC always includes a central processing unit (CPU).
2.System Memory: It might also include system memory (RAM).
3.Peripheral Controllers: SoCs can integrate peripheral controllers for USB, storage, and other I/O devices.
4.Advanced Peripherals: Additionally, more advanced peripherals like graphics processing units (GPUs), specialized neural network circuitry, and radio modems (for Bluetooth or Wi-Fi) can be part of an SoC.
5.Unlike traditional PCs with separate chips for CPU, GPU, and RAM, SoCs consolidate these components into a single package, making devices smaller, faster, cheaper, and more power-efficient12.
Historical Context:
6.The concept of integration has been a driving force in electronics since the 20th century.
7.In 1972, Intel introduced the first commercial single-chip microprocessor, combining CPU elements into a single integrated circuit.
8.Later, microcontrollers emerged—chips that integrated CPU, RAM, memory controller, serial controller, and more for embedded applications.





RISC-V(pronounced "risk-five") is an open standard instruction set architecture (ISA) rooted in reduced instruction set computer (RISC) principles. Here are the key points about RISC-V:

1. Open and Royalty-Free:
   - Unlike most other ISA designs, RISC-V is provided under **royalty-free open-source licenses.
   - This means that companies can use it without paying licensing fees, making it attractive for various hardware implementations¹.

2. Design Philosoph:
   - RISC-V follows the principles of a load–store architecture.
   - Its floating-point instructions adhere to the IEEE 754 floating-point standard**.
   - Notable features include:
     - Architecturally neutral design: Intended for practical use in various computer systems.
     - Variable-length extensions: Instructions can be 32-bit or any number of 16-bit parcels in length.
     - Support for embedded systems, personal computers, supercomputers, and parallel computers

3. Address Space Variants:
   - The specification defines 32-bit and 64-bit address space variants.
   - There's also a description of a 128-bit flat address space variant**, although it remains intentionally unfrozen due to limited practical experience with such large memory systems¹.

In summary, RISC-V is a revolutionary open-source ISA that allows software portability, hardware development, and custom processor creation across a wide range of application

Introduntion With OpenLane :
OpenLANE is an open-source ASIC (Application-Specific Integrated Circuit) design flow. It stands for "Open-Source VLSI (Very Large Scale Integration) Flow for a Full Custom ASIC Design". Essentially, it's a collection of tools and methodologies that enable the design, implementation, and verification of complex digital integrated circuits.

OpenLANE aims to provide a fully automated RTL to GDSII (Register Transfer Level to Graphic Data System) flow, meaning it takes a digital design expressed at a high level of abstraction (RTL) and converts it into a physical layout suitable for manufacturing. It integrates various open-source tools and scripts into a cohesive flow, allowing designers to take a design from conception through synthesis, placement and routing, timing analysis, and finally to tape-out (the finalization of the design for manufacturing).

The project emphasizes openness, collaboration, and reproducibility, which are crucial in the realm of semiconductor design. OpenLANE is developed and maintained by a community of researchers and engineers from academia and industry. It's gaining popularity due to its accessibility, transparency, and the ability to democratize the ASIC design process.
Process:


<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/5bc44b48-85fb-4dc2-adfb-113f2cc9155e">

<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/152512c1-9f4b-4789-bea2-8b3f1d6524da">

<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/6eff53d5-53c3-40d8-9fdc-5bd3c46b0ddc">


<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/54be9c3e-71a4-4ae5-949b-bda6abcbe983">


<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/ac291b77-773b-4def-a3d6-19704d72e2f1">


<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/08aa8264-e104-45c1-87f3-37ed5974d5c7">





<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/b5a38a35-f21a-486b-b6ed-6cb83624d8bc">


<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/951ba758-54af-4512-b657-731a146c46de">



<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/262dc00b-1a74-4366-9db8-dc6c9a4628d4">


<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/3797b3f0-9bfd-40a5-add0-a8993158e438">

<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/39244f19-332b-4b99-b575-d0774f862aaf">

<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/12bfe3b8-c788-4515-ba2f-16a3bf65b2ad">


Assignment 
FF ratio = number of d ff/ total cell
1613/14976=0.10842
Percentage of D ff’s =10.842%





