# UART-transreceiver-Implementation-Using-FPGA

This repository contains the implementation of a UART transceiver using FPGA. The project includes the design of both the transmitter and receiver using Verilog in Quartus Prime Lite software. We have also created a testbench for the transceiver and simulated it before uploading the code to the FPGA. Finally, we assigned the pins and used push buttons to observe UART communication between two FPGAs.

## Project Overview

### Components

- **FPGA Board:** The hardware platform for implementing the UART transceiver.
- **Quartus Prime Lite:** The software used for designing, simulating, and uploading the Verilog code to the FPGA.
- **Verilog:** The hardware description language used to implement the UART transmitter and receiver.
- **Push Buttons:** Used to control and observe UART communication between the two FPGAs.

### Functionality

- **UART Transmitter:** Designed to transmit serial data to the UART receiver.
- **UART Receiver:** Designed to receive serial data from the UART transmitter.
- **Testbench:** Created to simulate and verify the functionality of the UART transceiver.
- **Simulation:** Performed to ensure the correctness of the design before uploading to the FPGA.
- **Pin Assignment:** Pins were assigned on the FPGA to facilitate UART communication.
- **UART Communication:** Observed between two FPGAs using push buttons to control the data transmission and reception.

## Repository Structure

- `src/`: Contains the Verilog code for the UART transmitter and receiver.
  - `transmitter.v`: Verilog code for the UART transmitter.
  - `receiver.v`: Verilog code for the UART receiver.
- `testbench/`: Contains the testbench code for simulating the UART transceiver.
  - `uart_TB.v`: Testbench for the UART transceiver.
- `simulation/`: Contains the simulation files and results.
- `quartus/`: Contains Quartus Prime Lite project files.
- `docs/`: Documentation files, including this README and any additional guides or manuals.

## Contributors

- [Raveen Pramuditha](https://github.com/RPX2001)
- [Chandipa Janith](https://github.com/ChandeepaJanithPeiris)
- [Mavishan Pasira](https://github.com/Pasiramavishan)

## License

This project is licensed under the [MIT License](LICENSE).
