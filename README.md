# About the project

This software implements a BMS communication bridge between a battery system controlled by the 123electric SmartBMS and a GoodWe Hybrid Inverter (GW3648-EM).
It is currently running on a raspberry 3B, using a MCP2515 based board for the CAN communication with the inverter and serial communication with the BMS. 

The serial communication is based on the official 123electric/smartbms-thingspeak project.
The CAN communication and logic is based on the amazing yasko-pv/gw-ev project.