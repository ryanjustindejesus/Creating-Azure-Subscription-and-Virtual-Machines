<h1>Creating Azure Subscriptions and Virtual Machines</h1>
<b>This tutorial outlines the installation of Windows and Linux Virtual Machines using Microsoft Azure</b>

<h2>Environments and Technologies Used</h2>

- <b>Microsoft Azure</b> 
- <b>Remote Desktop</b>

<h2>Operating Systems</h2>

- <b>Windows 10</b>


<h2>Installation Steps</h2>

![windows-vm](https://github.com/user-attachments/assets/08220b5f-b9a5-4bdd-bb9b-aaf7c67fde9e)

- <b>Create Windows 10 Pro Virtual Machine</b></b>
- <b>Name: windows-vm</b>
- <b>Region: EAST US 2</b>
- <b>Resource Group: RG-Cyber-Lab</b>
- <b>Virtual Network: Lab-VNet</b>

![linux-vm](https://github.com/user-attachments/assets/452787b5-0905-467c-beeb-0625cabe4fd5)

- <b>Create Ubuntu (Linux) Pro Virtual Machine</b></b>
- <b>Name: linux-vm</b>
- <b>Region: EAST US 2</b>
- <b>Resource Group: RG-Cyber-Lab</b>
- <b>Virtual Network: Lab-VNet</b>

![windows nsg](https://github.com/user-attachments/assets/f15df672-d836-4b2d-813a-5fb9e5b5addd)
![linux nsg](https://github.com/user-attachments/assets/b8744d63-b29c-437d-99b8-d3d61489cb29)
- <b>Configure Network Security Group (Layer 4 Firewall) to allow all traffic inbound for both Windows and Linux virtual machines by typing * in the destination port ranges<b>
