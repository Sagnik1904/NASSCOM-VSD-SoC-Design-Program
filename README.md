# NASSCOM-VSD-SoC-Design-Program
# Day 1
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




# Day 2

''' **Chip floor planning** '''is a critical step in the physical design process of an integrated circuit (IC) or chip. It involves determining the placement of various functional blocks, such as logic cells, memory, and I/O pads, on the silicon die. This step is crucial because it directly impacts the performance, power consumption, and area (PPA) of the chip.

Here are some key aspects of chip floor planning:

1. **Area Allocation**: The chip area is divided into different regions to accommodate various functional blocks. These regions are typically allocated based on the size and importance of each block.

2. **Block Placement**: Once the areas are allocated, individual functional blocks are placed within these regions. The placement is determined based on factors such as connectivity, signal integrity, and timing requirements.

3. **Routing Channels**: Routing channels are reserved between the blocks to facilitate the routing of interconnects (wires) that connect the blocks. The width and spacing of these channels are determined based on the routing resources available and the density of interconnects.

4. **Power and Signal Integrity**: Considerations for power distribution and signal integrity are also taken into account during floor planning. Power lines and signal paths need to be laid out in such a way that they minimize voltage drop, noise, and signal delay.

5. Hierarchy: In larger designs, floor planning may involve hierarchical partitioning, where the chip is divided into multiple levels of abstraction, each with its own floor plan. This helps manage complexity and facilitates design reuse.

6. **Constraints**: Floor planning is guided by various design constraints, including timing, power, area, and manufacturability constraints. These constraints help ensure that the final layout meets the desired performance targets and can be manufactured reliably.

Overall, chip floor planning is a crucial early-stage design activity that sets the foundation for the rest of the physical design flow. Effective floor planning can significantly impact the overall quality and manufacturability of the chip.

**It's uses** : Chip floor planning on a silicon wafer involves optimizing the placement of multiple chips on a standard-sized wafer while considering die size, spacing, alignment, and manufacturing constraints. Maximizing wafer utilization and minimizing waste are crucial for cost-effectiveness. Chips are arranged in a regular grid pattern with adequate spacing for dicing and packaging. Proper orientation and alignment facilitate subsequent manufacturing steps. An exclusion zone near the wafer edge is often observed due to edge effects and potential defects.
<img width="590" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/00ad3b6a-70f7-4b0a-b606-1f3a8d526a00">

we use a formula to calculate the planning 
<img width="243" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/3f76779d-9a46-4910-8e96-17faa0591242">
***Power planning***
In integrated circuit (IC) design, power planning is a critical aspect aimed at managing power distribution efficiently across the chip. It involves strategizing the layout and routing of power lines to ensure uniform voltage supply while minimizing voltage drops and power dissipation. Through careful placement of power grids, decoupling capacitors, and voltage regulators, power planning aims to mitigate issues such as signal integrity degradation and electromagnetic interference. This process requires meticulous attention to detail, considering factors like current density, parasitic effects, and thermal management. By optimizing power delivery networks, IC designers can enhance performance, reliability, and energy efficiency, crucial for modern electronic devices with stringent power constraints. Effective power planning not only impacts the functionality of the chip but also influences its overall power consumption and heat dissipation characteristics, essential considerations in contemporary semiconductor design.
<img width="959" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/e0a28378-0c51-4c4c-8ca9-648d121158d5">
Power planning in IC design is indispensable for efficient power distribution across the chip, ensuring optimal voltage supply while minimizing voltage drops and power dissipation. It plays a crucial role in mitigating issues like signal integrity degradation and electromagnetic interference, essential for reliable chip performance. Through meticulous layout and routing of power lines, power planning enhances energy efficiency and thermal management, critical considerations in modern semiconductor design. Effective power planning not only influences chip functionality but also impacts power consumption and heat dissipation characteristics, contributing to overall device performance and longevity.
 ***Implemantation on OPENLANE :***
 
 <img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/e1421e35-f0ad-4b05-b7a8-da19de6c0e42">
<img width="416" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/c6fc5952-e8f5-4efb-9402-a55fde24349f">

**Using the command run_floorplan:**

<img width="415" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/f6de09f2-790b-4503-a423-32fbf50eb096">

**Using Magic-t**
<img width="256" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/eb8842d3-21fd-4708-9456-7eea3cac9085">

**Running placement**
<img width="303" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/de493956-00f7-40e4-9f50-12e147880ccf">


 # Day 3
  **I/O placer revision**
  <img width="291" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/4695fe22-56ed-47e3-a222-24ea8b575d40">
   **Clone of VSDstdcelldesign**
   <img width="361" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/edac3fda-85ed-4184-9b92-157d5ea5f30d">

   **Intro to basic layout and LEF using inverter***
<img width="241" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/3bd94354-5b14-4d42-99ba-8570d005ac82">
layout
<img width="195" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/827c7ac4-be7c-469c-a19f-d43d236c1d86">

**Graph Outcome:**
<img width="556" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/239e8ef5-9276-4b4b-b586-85f611840652">

# Day 4
 ***Pre-layout timing analysis and importance of good clock tree***

 Timing analysis with ideal clocks using openSTA:
 Timing analysis with ideal clocks using OpenSTA involves assessing the timing characteristics of a digital design without considering the complexities introduced by clock skew, jitter, or other non-idealities. OpenSTA, an open-source static timing analysis tool, enables designers to perform precise timing verification by analyzing the propagation delays of signals through the design's logic paths. By assuming ideal clock behavior, OpenSTA calculates the best-case and worst-case arrival times of signals at various points in the circuit, allowing designers to evaluate setup and hold time violations, clock-to-q delays, and overall timing performance. This analysis aids in ensuring that the design meets timing requirements and operates correctly under ideal conditions, serving as a fundamental step in the design verification process before considering real-world timing effects.
 .lif file 
 <img width="539" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/6a26b334-a4e2-4c53-89c4-7a95296149b2">

after that we  need toedit the config.tcl 
**The result after synthesis is :**
<img width="547" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/4d2d2426-5e62-42c9-92a1-5b4774b4e940">
 tns= 759.4
 wns= 24.8
 then:
 <img width="153" alt="image" src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/ade83b6f-e8c1-4db4-aa88-6b2fd8ebf9d6">
the chip model area is :18730.544
<img width="210" alt="image" 
   src="https://github.com/Sagnik1904/NASSCOM-VSD-SoC-Design-Program/assets/143477873/b85fca6a-0919-4652-a104-db4b12fc05a4">




