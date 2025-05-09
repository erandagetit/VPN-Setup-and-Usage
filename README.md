# VPN-Setup-and-Usage
</p>
<img src=https://i.imgur.com/HIbXzfF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>








Azure Virtual Machine and VPN Lab
This tutorial walks you through setting up a virtual machine in Microsoft Azure, testing VPN connections, and observing the changes in IP addresses.

Part 1: Create a Virtual Machine in Azure
Access Your Public IP Address

On your own machine, browse to WhatIsMyIPAddress.
Take note of your public IP address and save it in a text file for reference.
Create a Resource Group

Log into your Azure Portal: Azure Portal.
Navigate to Resource Groups and click Create.
Provide the following:
Resource Group Name: MyAzureVPNLab
Region: Select a region near you.
Click Review + Create, then Create.
Create a Virtual Machine

Navigate to Virtual Machines in the Azure Portal and click Create.
Select Azure Virtual Machine.
Fill out the following:
Name: MyWindowsVM
Region: Choose a region close to your geographic location or country from your current location.
Image: Windows 10 22H2.
Size: Select a size that has at least 2vcpus, and 8GiB memory.
Administrator Username and Password: Set your credentials.
Acknowledge licensing agreement & ensure Inbound Port Rules to allow RDP (Remote Desktop Protocol).
Click Review + Create, then Create.
</p>
<img src=https://i.imgur.com/nxAImFM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/XL3BSp6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

4. Log into the Virtual Machine
- After the VM is created, navigate to it in the Azure Portal.
- Copy the Public IP Address of your VM.
   - Use Remote Desktop to connect to the VM:
   - Remote Desktop Address: Enter the Public IP Address of the VM.
Username and Password: Use the credentials you created earlier.
Once connected, open a web browser on the VM
</p>
</p>
<img src=https://i.imgur.com/RIv4qAx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

5. Check the VM's Public IP Address
In the VM, browse to WhatIsMyIPAddress.
Take note of the VM's public IP address and save it in a text file.

Part 2: Sign Up for ProtonVPN and Test the VPN Connection
<hr>
1. Sign Up for ProtonVPN

On your actual computer, go to ProtonVPN Sign-Up.
Create a free account.

2. Download ProtonVPN Client

In your VM, go to ProtonVPN Download.
Download and install the ProtonVPN client.

3.Log Into ProtonVPN

Open the ProtonVPN client in the VM.
Log in using your ProtonVPN account credentials: ProtonVPN Login.

4.Connect to a VPN Server

In the ProtonVPN client, choose a VPN server in a area different from your actual computer's location (Proton VPN requires payment to change countries).
Connect to the VPN server.
</p>
<img src=https://i.imgur.com/g0TyeSp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>

5. Check the VPN's Public IP Address
- In the VM, browse to WhatIsMyIPAddress.
- Take note of the new IP address and save it in a text file.

Notes and Observations
<hr>

- Save all IP addresses and observations in a text file for documentation purposes.
- Compare the behavior of websites and the changes in IP addresses to understand the effects of geographic location and VPN usage.
- From this lab, here are my documented IP addresses & their changes:
  
</p>
</p>
</p>
Personal Computer
<img src=https://i.imgur.com/oQL7wpD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
VM - Non-VPN
<img src=https://i.imgur.com/US4YRFP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
VM - VPN
<img src=https://i.imgur.com/d63JpLq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

