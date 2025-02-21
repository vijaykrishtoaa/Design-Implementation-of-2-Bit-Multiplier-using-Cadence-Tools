# Design and Simulation of a 4-Bit Adder Using Verilog and Cadence Genus
Ex No: 07     Design and Simulation of a 4-Bit Adder Using Verilog and Cadence Genus   

**Aim:**
To design and simulate a 4-bit adder using Verilog HDL and synthesize the design using Cadence Genus to analyze its performance metrics.

**Tools Required:**
   Personal Computer
   Cadence Genus Software

**Procedure:**

Open Terminal and Navigate to Workspace
Load the Cadence Environment
Launch Cadence Genus
Create a New Project in Cadence Genus
  Open Genus GUI
  Create a New Project
  Set the working directory
Add Verilog Design Files
  Import the four_bit_adder.v file
  Set four_bit_adder as the Top Module
Specify Standard Cell Library
  Assign a technology library (e.g., 45nm.lib)
  Set constraints like clock period and power limits
Run Synthesis Using TCL Script:
  Go to Synthesis → Start Synthesis
  Choose RTL-to-Gate-Level Mapping
  Click Run
Analyze Synthesized Design:
  Open Schematic Viewer to inspect the gate-level representation
  Check timing analysis (Report → Timing)
  Check area and power reports (Report → Area / Power)
**Verilog HDL Program for 4-Bit Adder:**
  
  
  
  

**Simulation Output**


Result:
The 4-bit adder was successfully designed and simulated using Verilog HDL. The design was synthesized in Cadence Genus, and reports for area, power, and timing were generated.
