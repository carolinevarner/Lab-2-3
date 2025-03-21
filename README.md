# README: 5-Bit Digital Memory & Computer Design (Lab 2 & 3)

## **Project Overview**  
This project involves the design and simulation of a **5-bit stored-program computer** using **NI Multisim**. The design follows a **von Neumann architecture**, where both program instructions and data share the same memory space. The computer uses a **Load-Store hybridized with Accumulator (AC) machine architecture**, featuring a **5-bit word size** and **3-bit addressable memory**.

## **Lab 2: 5-Bit Digital Memory Design**  
### **Objective**  
To design and simulate a **5-bit digital memory unit** that includes:  
1. **A memory module** with 8 addressable locations, each storing a 5-bit word.  
2. **A 3-to-8 decoder** to select memory locations.  
3. **An 8-to-1 multiplexer** to read data from selected memory locations.  

### **Components and Design**  
- **Memory Unit:** Each memory location consists of **D flip-flops** to store a 5-bit word.  
- **3-to-8 Decoder:** Takes a 3-bit address and enables the corresponding memory location.  
- **8-to-1 Multiplexer:** Reads data from the selected memory location.  
- **Manual Control:** A **SPDT switch** is used for manually updating flip-flops.  
- **Output Display:** The stored memory values are displayed using **Probes and a DCD_Hex_Dig_RED display**.

### **Tasks**  
- Implement the memory unit in **NI Multisim**.  
- Store **Program-1** in memory and verify memory read/write operations.  
- Submit screenshots of:  
  1. Full memory unit circuit.  
  2. Focused view of the **decoder**.  
  3. Focused view of the **multiplexer**.  
  4. Memory unit with **Program-1** stored in it.  

---

## **Lab 3: 5-Bit Digital Computer Design**  
### **Objective**  
To build a **5-bit digital computer** capable of executing basic instructions using an **Arithmetic Logic Unit (ALU) and Registers**.  

### **Computer Specifications**  
- **Instruction Set (ISA):**  
  - **Load (00)** – Load value from memory to AC.  
  - **Store (01)** – Store AC value into memory.  
  - **Add (10)** – Perform addition using AC and MBR.  
  - **AND (11)** – Perform logical AND between AC and MBR.  
- **Registers:**  
  - **Accumulator (AC)** – Stores intermediate computation results.  
  - **Memory Buffer Register (MBR)** – Holds operand for arithmetic/logical operations.  
  - **Instruction Register (IR)** – Holds the fetched instruction.  
  - **Memory Address Register (MAR)** – Holds the memory address being accessed.  
- **ALU:** Supports **addition** and **AND operations**.  

### **Tasks**  
- Implement the **ALU and registers** in **NI Multisim**.  
- Manually generate control signals for execution.  
- Execute **Program-1 and Program-2**, capturing screenshots:  
  1. Before program execution.  
  2. After execution of each instruction.  

---

## **Installation Instructions**  
1. **Download and install NI Multisim** ([Link](https://www.ni.com/en/support/downloads/software-products/download.multisim.html)).  
2. If using **KSU Virtual Desktop**, follow the **D2L instructions** for access.  
3. **Alternative:** Use the **NI Multisim Online** version ([Link](https://www.multisim.com)).  

---

## **Contributors**  
- Caroline Varner
- Course: CS 3502 - Operating Systems
- Instructor: Waqas Majeed
- University: Kennesaw State University
