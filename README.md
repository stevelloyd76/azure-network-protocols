<p align="center">
<img width="378" alt="image" src="https://github.com/nkgarrett/NSG-Inspecting-Traffic/assets/156832893/5c77bf9a-8d0b-48cf-bf0e-50c3387964ab">


# Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines


## Environments and Technologies Used

**Microsoft Azure (Virtual Machines/Compute)**
**Remote Desktop**
**Various Command-Line Tools**
**Various Network Protocols (SSH, RDP, DNS, HTTP/S, ICMP)**
**Wireshark (Protocol Analyzer)**

### Operating Systems Used

**Windows 10 (22H2)**

**Ubuntu Server 20.04**

## High-Level Steps

1. **Create Azure Virtual Machines**
2. **Configure Network Security Groups (NSGs)**
3. **Install Wireshark on VMs**
4. **Observe Traffic Using Wireshark**

## Actions and Observations

### Step 1: Create Azure Virtual Machines

1. Create a Windows 10 Virtual Machine (VM) on Azure.
2. Create a Ubuntu Server 20.04 Virtual Machine on Azure.

### Step 2: Configure Network Security Groups (NSGs)

1. Define NSG rules to allow/deny traffic between VMs.
2. Associate NSGs with VMs.

### Step 3: Install Wireshark on VMs

1. Connect to Windows 10 VM via Remote Desktop.
2. Install Wireshark on Windows 10 VM.
3. Connect to Ubuntu Server VM via SSH.
4. Install Wireshark on Ubuntu Server VM.

### Step 4: Observe Traffic Using Wireshark

1. Launch Wireshark on both VMs.
2. Filter traffic by protocol (e.g., ICMP, SSH, RDP, DNS).
3. Initiate traffic between VMs (e.g., ping, SSH connection, RDP session).
4. Observe captured traffic in Wireshark.
5. Analyze traffic patterns and verify NSG rules effectiveness.
