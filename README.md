markdown
# Modbus RTU Multi-Slave Communication with TIA Portal

A sample project for implementing and documenting **Modbus RTU** communication between a Siemens PLC (programmed in **TIA Portal**) as **Master** and **multiple Slaves** over an RS-485 serial link.

## 🎯 Project Goal
- Set up Modbus RTU communication with multiple Slaves
- Manage Slave addressing, polling scheduling, and error recovery
- Provide reusable sample code and function blocks

## 🧩 Project Components
- **Master**: Siemens PLC (S7-1200 ) in TIA Portal
- **Slaves**: Multiple Modbus RTU devices ( drives)
- **Libraries**: MB_COMM_LOAD / MB_MASTER and helper blocks

## ⚙️ Prerequisites
- TIA Portal (specify version, e.g., V16 or V17)
- Modbus RTU-compatible PLC (S7-1200)
- RS-485 serial communication module (e.g., CB 1241 RS485 for S7-1200) or the relevant serial port
- Slave devices or a Modbus RTU simulator (e.g., Modbus Slave / QModMaster)

## 🚀 How to Use
1. Open the project in TIA Portal.
2. Configure serial port parameters (baud rate, parity, stop bits) and each Slave address (Unit ID).
3. Edit Modbus parameters (registers, data length).
4. Download and run the program, then verify communication.
