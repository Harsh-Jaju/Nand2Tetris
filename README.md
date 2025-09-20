# Built a Computer from First Principles (Nand to Tetris I)  

Course projects are based on [Nand2Tetris](https://www.nand2tetris.org/).  
The course takes a bottom-up approach to computer systems — starting with simple logic gates and step by step building towards a complete 16-bit computer capable of running programs.  

---

## Overview  

The work progresses in stages:  
- Begin with primitive gates and gradually design higher-level chips.  
- Construct memory units, CPU, and eventually the entire Hack computer.  
- Write an assembler that translates Hack assembly code into binary instructions.  

All hardware modules were implemented in **HDL**, while the assembler was developed in **C++**.  

---

## Project 1–3  

- Designed elementary logic gates from the NAND gate upwards.  
- Built combinational components such as adders and multiplexers.  
- Implemented sequential circuits including registers and memory units, forming the basis for RAM and control elements.  

---

## Project 4  

- This project focuses on the building of programs using the **Hack assembly language**.  
- We were required to build 2 programs that worked with **RAM, the virtual screen, and keyboard input**, showcasing low-level manipulation of memory and I/O.  

---

## Project 5  

- Combined all components (ALU, memory, and control logic) to implement a functional **CPU**.  
- Integrated CPU and memory modules to build the full **Hack computer**, capable of executing Hack assembly programs.  

---

## Project 6  

- Developed a **two-pass assembler** in **C++**.  
- The assembler translates Hack assembly into machine code, handling labels, symbols, and predefined variables.  
