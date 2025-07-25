# ⚙️ I/O Module Configuration: AL1302

## 🔧 Step 1: Add AL1302 Module to the Project

### Search for the Module
Type: AL1302

This module setup includes 1 Master and 2 Slave input modules connected via 2 ports.

### Add Module
   
Ensure all connected input modules are properly assigned in the hardware configuration.

### Set I/O Addresses
   
Open the Device Configuration.

Check the default input/output addresses.

Modify them as needed to match your project's I/O mapping.

<img width="1205" height="384" alt="image" src="https://github.com/user-attachments/assets/da660252-93d2-45fa-8455-b8ecc4638ae2" />

## Step 2: Set Ethernet IP Address for AL1302

Select the AL1302 Master module in the Device Configuration.

Navigate to the Ethernet Addresses tab.

Assign the following IP Address: 192.168.8.61 

<img width="1209" height="828" alt="image" src="https://github.com/user-attachments/assets/724dc177-078b-4659-84ae-1f85396ac4a8" />


## 🔌 Step 3: Connect AL1302 to PLC in Network View

Open the Network View in TIA Portal.

Drag a connection line from the PLC to the AL1302 Master module.

Ensure proper PROFINET communication is established.

<img width="724" height="384" alt="Screenshot 2025-07-25 110438" src="https://github.com/user-attachments/assets/1841fd50-4df1-4561-8168-8f517934d8ad" />


