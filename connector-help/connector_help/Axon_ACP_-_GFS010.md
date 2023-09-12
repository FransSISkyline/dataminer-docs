---
uid: Connector_help_Axon_ACP_-_GFS010
---

# Axon ACP - GFS010

The GFS010 is a 3 Gb/s, HD, SD frame synchronizer.

The **Axon ACP - GFS010** driver can be used to display and configure information related to this device.

## About

This driver is automatically generated by the driver **Axon ACP**.

There are different possibilities available for **alarm monitoring** and **trending**.

### Ranges of the driver

| **Driver Range** | **Description**                   | **DCF Integration** | **Cassandra Compliant** |
|------------------|-----------------------------------|---------------------|-------------------------|
| 1.0.3.x          | Change in discrete display values | Yes                 | Yes                     |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.3.x          | 6038, 6042                  |

## Installation and configuration

### Creation

This element is automatically created by the parent element using the **Axon ACP** driver.

## Usage

The element has the following data pages:

- **General**: This page displays general information about the card: **Card Name**, **Card Description**, **SW Revision**, **HW Revision**, etc.
- **Status**
- **I/O**
- **GPI**
- **Options**
- **Video**
- **Inserter**
- **Embedder A/B**
- **Embedder C/D**
- **Network**
- **Alarm Priority**: This page displays the event messages of the card, i.e. special messages generated asynchronously on the card.

## DataMiner Connectivity Framework

The Axon ACP protocol supports the usage of DCF and can only be used on a DMA with **8.5.4** as the minimum version.

DCF can also be implemented through the DataMiner DCF user interface and through DataMiner Third Party protocols (for instance a manager).

Connectivity for this protocol is managed by the parent protocol Axon ACP.

### Interfaces

#### Physical Interfaces

- **SDI Input**: A single fixed interface of type **input**.
- **SDI Output 1**: A single fixed interface of type **output**.
- **SDI Output 2**: A single fixed interface of type **output**.
- **SDI Output 3**: A single fixed interface of type **output**.
- **SDI Output 4**: A single fixed interface of type **output**.

### Connections

#### Internal Connections

When a DVE child element is created, the following connections are established:

- Between **SDI Input** and **SDI Output 1**.
- Between **SDI Input** and **SDI Output 2**.
- Between **SDI Input** and **SDI Output 3**.
- Between **SDI Input** and **SDI Output 4**.