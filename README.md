# My_CPU

📖 Introduction
This project implements a Custom CPU Architecture using Logisim Evolution. The design includes an Arithmetic Logic Unit (ALU), Registers, Control Unit, and Memory components to execute fundamental operations.


✨ Features

✅ ALU Operations → Supports addition, subtraction, AND, OR, etc.
✅ Register File → Stores temporary values for processing.
✅ Control Unit → Decodes and manages instruction execution.
✅ Clock-Driven Execution → Step-by-step operation via clock pulses.
✅ RAM & ROM Integration → Supports instruction and data storage.

📂 File Structure

bash
Copy
Edit
/CPU_Design
│── 2107086_Updated_CPU.circ  # Main CPU circuit
│── 2107086_cpu.circ          # CPU core logic
│── 2107086_ALU.circ          # Arithmetic Logic Unit (ALU)
│── README.md                 # Documentation file


🚀 How to Run the Project:

🔹 Steps to Open in Logisim Evolution
1️⃣ Download and Install Logisim Evolution → https://logisim-evolution.org
2️⃣ Open Logisim Evolution.
3️⃣ Click "File → Open" and select 2107086_Updated_CPU.circ.
4️⃣ Use "Simulate → Tick Once" to execute step-by-step.
5️⃣ Observe the registers, ALU, and memory changes during execution.

🔍 Debugging & Common Issues

🔹 Red Wire Errors (Floating Inputs)
Ensure all inputs have defined values (use constants if needed).
Check the Control Unit signals for proper instruction execution.
🔹 Clock Not Working
Ensure the clock is connected to sequential components.
Use "Tick Frequency → Slow" to debug step-by-step execution.
🔹 ALU Incorrect Outputs
Check if the MUX selects the correct ALU operation.
Verify that input values match expected results.
🛠 Future Improvements
🚀 Add pipeline stages for faster execution.
🚀 Implement interrupt handling for advanced functionality.
🚀 Improve instruction set support to handle more complex operations.

📜 License

This project is open-source. Feel free to use, modify, and contribute!


💡 Conclusion
This project demonstrates CPU architecture design in Logisim, focusing on the ALU, registers, memory, and control unit. It provides a foundation for learning computer organization and digital logic.
