# FPGA LED & Switch Control using Vitis

This project uses the **Real Digital Blackboard (Zynq-7000)** FPGA board to control on-board LEDs using physical switches. The system is programmed in **C** using **Xilinx Vitis** and run on the ARM core of the Zynq SoC.

## 🛠 Tools & Technologies

- **Board**: Real Digital Blackboard (Xilinx Zynq-7000)
- **Language**: C
- **IDE**: Xilinx Vitis
- **Communication**: Memory-mapped I/O (direct register access)

## 🔌 How It Works

- The C program reads input from physical slide or push switches.
- Based on the switch state, the program controls the on-board LEDs.
- This is done via direct memory access to the FPGA’s GPIO registers.



