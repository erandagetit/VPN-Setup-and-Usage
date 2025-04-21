# VPN-Setup-and-Usage
</p>









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


