---
layout: default
---

## Smart Charging system

This project is a battery charger and monitoring system that interfaces with the battery's Battery Management System (BMS). The driver file (mod_ID1) interrogates the BMS, retrieves data, and forwards it to both the graphical user interface (GUI) for user control and to a deadicated private network. 

A server socket file receives data words as TCP packets from the BMS, formatted using the MODBUS protocol. This server socket runs on a virtual machine (VM) within a private network. It converts the incoming TCP data to UDP format, making it compatible with OpenRVDAS for streamlined data handling.



![image](https://github.com/user-attachments/assets/d2a73756-a9f7-4999-a208-463f40c24fb7)
_Linux-GUI-Driver-and-Server-Socket - Completed_

[back](./)
