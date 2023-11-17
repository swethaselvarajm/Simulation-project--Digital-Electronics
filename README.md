# DESIGN AND SIMULATE THE LOGIC DIAGRAM USING VERILOG

# AIM:
To Design and simulate the logic diagram using Verilog.

# EQUIPMENTS REQUIRED:
Hardware – PCs, Cyclone II , USB flasher.

Software – Quartus prime.

# PROCEDURE:

# Step 1:

Create module encoder and decoder.

# Step 2:

Get inputs and outputs for encoders and decoders.

# Step 3:

perform or operation for encoder and and logic for decoders.

# Step 4:

perform RTL LOGIC and get waveform.

# Step 5:

End the module.

# LOGIC DIAGRAM:

![image](https://github.com/swethaselvarajm/Simulation-project--Digital-Electronics/assets/119525603/192afdd5-09ff-4d1d-bcee-5b93e348f39d)

# NETLIST DIAGRAM:
 
![image](https://github.com/swethaselvarajm/Simulation-project--Digital-Electronics/assets/119525603/f9bf5e4d-8d4f-4906-bfdd-fddc6371478a)

# TIMING DIAGRAM:

![image](https://github.com/swethaselvarajm/Simulation-project--Digital-Electronics/assets/119525603/5238e1f8-9dc6-4bb8-b596-e556dd9b8bbf)

# TRUTH TABLE :

![image](https://github.com/swethaselvarajm/Simulation-project--Digital-Electronics/assets/119525603/0ca20176-dd8e-49da-99ef-d3993d06c991)

# PROGRAM:
```
Program to To Design and simulate the logic diagram using Verilog.
Developed by: SWETHA.S
RegisterNumber: 212222230110
module e13(x,y1,y2,z1,z2):
Input x,y1,y2;
Output z1,z2;
Assign z1=(x&y) | ((~x) & y2);
Assign z2=((~x)&y2) | (x&(~y1));
endmodule
```
# RESULT:
Thus the program to design and simulate the logic diagram using Verilog.
