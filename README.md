<h1>🚀 My_CPU</h1>

<h2>📖 Introduction</h2>
<p>This project implements a <strong>Custom CPU Architecture</strong> using Logisim Evolution. The design includes an <strong>Arithmetic Logic Unit (ALU), Registers, Control Unit,</strong> and <strong>Memory components</strong> to execute fundamental operations.</p>

<h2>✨ Features</h2>
<ul>
  <li>✅ <strong>ALU Operations</strong> → Supports addition, subtraction, AND, OR, and other basic arithmetic and logical operations. The ALU performs these operations based on the input instructions.</li>
  <li>✅ <strong>Register File</strong> → Stores temporary data values that the CPU needs for immediate operations, helping improve processing efficiency and speed.</li>
  <li>✅ <strong>Control Unit</strong> → Decodes the instruction and controls the execution of the CPU, coordinating how data flows between components such as ALU, memory, and registers.</li>
  <li>✅ <strong>Clock-Driven Execution</strong> → Uses clock pulses to execute operations step-by-step, allowing for synchronization and controlling the flow of instructions in a sequential manner.</li>
  <li>✅ <strong>RAM & ROM Integration</strong> → Integrates memory for data storage (RAM) and instruction storage (ROM), enabling the CPU to access data and execute instructions effectively.</li>
</ul>

<h2>📂 File Structure</h2>

<pre>
/CPU_Design
│── 2107086_Updated_CPU.circ  # Main CPU circuit
│── 2107086_cpu.circ          # CPU core logic
│── 2107086_ALU.circ          # Arithmetic Logic Unit (ALU)
│── README.md                 # Documentation file
</pre>

<h2>🚀 How to Run the Project</h2>

<h3>🔹 Steps to Open in Logisim Evolution</h3>
<ol>
  <li>Download and Install Logisim Evolution → <a href="https://logisim-evolution.org" target="_blank">Logisim Evolution</a></li>
  <li>Open Logisim Evolution.</li>
  <li>Click <strong>"File → Open"</strong> and select <code>2107086_Updated_CPU.circ</code>.</li>
  <li>Use <strong>"Simulate → Tick Once"</strong> to execute step-by-step.</li>
  <li>Observe the registers, ALU, and memory changes during execution.</li>
</ol>

<h2>🔍 Debugging & Common Issues</h2>

<h3>🔹 Red Wire Errors (Floating Inputs)</h3>
<ul>
  <li>Ensure all inputs have defined values (use constants if needed).</li>
  <li>Check the Control Unit signals for proper instruction execution.</li>
</ul>

<h3>🔹 Clock Not Working</h3>
<ul>
  <li>Ensure the clock is connected to sequential components.</li>
  <li>Use <strong>"Tick Frequency → Slow"</strong> to debug step-by-step execution.</li>
</ul>

<h3>🔹 ALU Incorrect Outputs</h3>
<ul>
  <li>Check if the MUX selects the correct ALU operation.</li>
  <li>Verify that input values match expected results.</li>
</ul>

<h2>🛠 Future Improvements</h2>
<ul>
  <li>🚀 Add pipeline stages for faster execution.</li>
  <li>🚀 Implement interrupt handling for advanced functionality.</li>
  <li>🚀 Improve instruction set support to handle more complex operations.</li>
</ul>

<h2>📜 License</h2>
<p>This project is open-source. Feel free to use, modify, and contribute!</p>

<h2>💡 Conclusion</h2>
<p>This project demonstrates <strong>CPU architecture design</strong> in Logisim, focusing on the <strong>ALU, registers, memory,</strong> and <strong>control unit</strong>. It provides a foundation for learning <strong>computer organization</strong> and <strong>digital logic</strong>.</p>
