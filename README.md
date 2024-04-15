# HALF_SUBTRACTOR
# Aim
To simulate and synthesis half subtractor using Xilinx ISE.

# APPARATUS REQUIRED:
vivado 2023.2 software.

# PROCEDURE:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)

# Program
```
module half_subtractor(a,b,diff,borr);
input a,b; 
output diff,borr; 
wire x;
xor (diff,a,b);
not (x,a);
and (borr,x,b); 
endmodule
```
# Output
![image](https://github.com/KabilanBaskaran0807/HALF_SUBTRACTOR/assets/166724685/d480e6e8-54f2-4189-b164-9a5028b833d1)


# Result
Thus the verilog program for half subtractor has been simulated and verified successfully.

