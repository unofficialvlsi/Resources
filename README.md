# VLSI Digital Design Interactive Session – README

Welcome to the **VLSI Chapter – Tarang Club** interactive session on **Digital Design in VLSI**. This README contains all necessary resources, tools, references, and links to help you get started with HDL, Verilog, and VLSI fundamentals.


---

## 🧭 **VLSI Roadmap for Beginners**
1. **Digital Electronics Fundamentals** – Logic gates, combinational & sequential circuits  
2. **HDL Basics** – Why HDL, RTL design flow  
3. **Verilog/SystemVerilog** – Syntax, modules, testbenches  
4. **Simulation Tools** – Writing & running Verilog code  
5. **Synthesis Tools Intro** – Basic flow and constraints  
6. **Mini Projects** – ALU, FSMs, Adder/Subtractor, UART, SPI  
7. **Advanced Topics** (optional) – DFT, STA, ASIC/FPGA flows

---

## 🛠️ **Tools You Should Install**
### **1. VS Code**  
A lightweight editor for writing Verilog.  
Download: https://code.visualstudio.com/

### **2. Icarus Verilog (iverilog)**  
Free Verilog simulator for executing Verilog code.  
Installation Guide: https://steveicarus.github.io/iverilog/

### **3. GTKWave**  
Tool for viewing waveform outputs.  
Download: https://gtkwave.sourceforge.net/

### **4. EDA Playground (Online)**  
No installation required. Perfect for beginners.  
https://www.edaplayground.com/

---

## ▶️ **Best YouTube Playlists & Channels**
### **1. Verilog Basics**
- NPTEL - Hardware Modelling Using Verilog: [YouTube](https://www.youtube.com/playlist?list=PLRsFfXmDi9IYCNlvNjrsD8bLMmNE0UxBH)  
- Neso Academy – Verilog: https://www.youtube.com/playlist?list=PLLy_2iUCG87C2vZqUoOYwZ2Ck2aSFFmMm

### **2. Digital Electronics Revision**
- Gate Smashers: https://www.youtube.com/playlist?list=PLxCzCOWd7aiH2wwES9vPWsEL2xQGd4o6M  
- Neso Academy DE: https://www.youtube.com/playlist?list=PLBlnK6fEyqRiVhbXDGLXDk_OQAeuVcp2O

### **3. VLSI Industry Insights**
- VLSI Junction: https://www.youtube.com/c/VLSIJunction  
- SemiPoint: https://www.youtube.com/c/SemiPoint

---

## 📚 **Recommended Books**
- *Digital Design* by Morris Mano  
- *HDL Programming* by Nazeih Botros  
- *Verilog HDL* by Samir Palnitkar  
- *CMOS VLSI Design* by Weste & Harris

---

## 💡 **Starter Verilog Examples**
### **1. Basic AND Gate**
```verilog
module and_gate(input a, input b, output y);
    assign y = a & b;
endmodule
```

### **2. 4-bit Adder**
```verilog
module adder4(input [3:0] a, input [3:0] b, output [4:0] sum);
    assign sum = a + b;
endmodule
```

### **3. Simple Testbench**
```verilog
module tb;
    reg a, b;
    wire y;

    and_gate uut(a, b, y);

    initial begin
        a = 0; b = 0;
        #10 a = 1;
        #10 b = 1;
        #20 $finish;
    end
endmodule
```

---

## 📝 **Practice Problems**
- Implement a 2:1 mux  
- Write Verilog for 3-bit counter  
- Build a sequence detector (101)  
- Design an ALU supporting 4 operations

---

## 🧪 **Mini Projects for Beginners**
- 4-bit Ripple Carry Adder  
- Traffic Light Controller using FSM  
- UART Transmitter  
- Simple Register File

---

## ✔️ **Registration Link**
(Attach Google Form link here)

---

## 🙌 **Contact**
For queries, reach out to the VLSI Chapter representatives of Tarang Club.

---

## ⭐ **We look forward to meeting you!**
