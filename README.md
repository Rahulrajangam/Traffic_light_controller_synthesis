# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic :
![Screenshot 2025-05-15 112107](https://github.com/user-attachments/assets/e31330ac-f39f-4fcc-b637-bd0b7dd75914)

### Area report:
![Screenshot 2025-05-15 112136](https://github.com/user-attachments/assets/1c741b37-1e6d-4802-af0c-b77eef9785dc)

### Power Report:
![Screenshot 2025-05-15 112241](https://github.com/user-attachments/assets/a71ba3f2-634b-44ea-a41d-6cee79d59f40)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
