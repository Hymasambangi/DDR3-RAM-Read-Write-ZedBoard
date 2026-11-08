
# DDR3 RAM Read and Write Implementation using ZedBoard

## Project Overview
This project demonstrates DDR3 RAM read and write operations using the Zynq-7000 Processing System on the Xilinx ZedBoard.

## Tools Used
- Xilinx Vivado 2021.2
- Vitis IDE 2021.2
- Embedded C

## Hardware
- Digilent ZedBoard
- Zynq-7000 SoC
- Onboard DDR3 RAM

## Implementation
- Configured the Zynq Processing System in Vivado.
- Enabled the DDR3 memory interface.
- Developed an Embedded C application in Vitis IDE.
- Wrote data into DDR3 memory.
- Read the stored data and verified it.

## Test Data
Write Data: `0x12345678`

Expected Read Data: `0x12345678`

## Result
DDR3 memory read and write operations were implemented and verified on the ZedBoard.

## Author
Sambangi Hymavathi


## Project Screenshots

### Vivado Block Design
![Vivado Block Design](screenshots/Block%20Design.jpeg)

### Vitis C Code
![Vitis Code](screenshots/Vitis%20code.jpeg)

### DDR3 Read/Write Output
![DDR3 Output](screenshots/DDR%20Output.jpeg)
