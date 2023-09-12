---
uid: Connector_help_Cisco_Panorama_CL
---

# Cisco Panorama CL

This driver is used to display information related to the **Cisco Panorama CL** device.

## About

This driver uses SNMP to communicate with the **Cisco Panorama CL** device.

## Installation and configuration

### Creation

This driver uses a Simple Network Management Protocol (SNMP) connection and needs the following user information:

**SNMP Connection:**

- **IP Address/host**: The polling IP of the device, e.g. *10.145.1.12*.

**SNMP Settings:**

- **Port number**: The port of the connected device, by default *161*.
- **Get community string**: The community string required to read from the device. The default value is *public*.
- **Set community string**: The community string required to set to the device. The default value is *public*.

## Usage

### General Page

This page displays Communication Layer rates, such as the **Successful Connection Rate**, **Failed Sessions Rate**, etc.

### Traps Page

This page displays a table with the traps received from the device.