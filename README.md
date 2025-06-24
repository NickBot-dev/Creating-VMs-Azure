<p align="center">

![image](https://github.com/user-attachments/assets/9222473a-edde-4c63-adb2-ddcfc89c9771)

</p>

<h1>Creating a Windows and Linux Virtual Machine with Microsoft Azure</h1>


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure and Virtual Machines

<h2>Operating Systems Used </h2>

- Windows 10 Pro
- Linux Ubuntu

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM) and select the previously created Resource Group. Allow VM to create a new Virtual Network (Vnet) and Subnet
- Create a Linux (Ubuntu) VM and select the previously created Resource Group and Virtual Network. The Windows and Linux Virtual Networks MUST BE THE SAME
- Specify Credentials, check Licensing Agreement and click "Review and Create" 

<h2>Deployment and Configuration Steps</h2>

<p>
    
 ![Screenshot 2025-06-24 100735](https://github.com/user-attachments/assets/de4c5463-31d5-44c7-b95d-f3e1b4a3439e)
 ![Screenshot 2025-06-24 101222](https://github.com/user-attachments/assets/821e81f3-4fdb-4cdd-98c9-aa309f4bd678)

</p>
<p>
From the Azure home page, click on "Resource Groups" and select "create new" Resource Group. Specify your Subscription, Resource Group Name, and Region. Click "Review and Create" 
</p>
<br />

<p>

 ![Screenshot 2025-06-24 103202](https://github.com/user-attachments/assets/0869a86d-ec7f-421b-84e9-cefca25c023f) 

</p>
<p>
From the Azure home page, click on Virtual Machines and select "Create New", Virtual Machine. Select the previously created Resource Group, Virtual Machine Name, Region, and Zone. Select "Windows 10 Pro" Image and at least 2 Virtual CPU's (vcpus)
</p>
<br />

<p>

 ![Screenshot 2025-06-24 103746](https://github.com/user-attachments/assets/eca250d0-143f-4099-a600-5aa3da3aada7)

</p>
<p>
From the Networding tab, we'll need to specify a name for our Virtual Network. This is important because the Linux VM must have the same Virtual network Name. The rest is set by default and we now click "Review and Create"  
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/7836b4a2-708a-49d3-9af8-62ced2c2b575)

</p>
<p>
After the VM is successfully deployed, you can click on "Resource Groups" from the home page to view contents. You will notice the Virtual Network name, Virtual Machine name, Public IP Address, Network Security Group (NSG), Network Interface Card (NIC), and Disk   
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
