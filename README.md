<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop (RDP)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL

<h2>Deployment and Configuration Steps</h2>

<p>

![image](https://github.com/user-attachments/assets/0518c45f-4265-4230-a38d-fa0470d7d2b0)
</p>
<p>
First, we’ll create a resource group in Azure named osTicket. Then, we’ll create a virtual machine inside that group, using Windows 10  and making sure that he has at least a 2 vCPU. 
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/a02112ea-2fdc-475e-998b-14add626382e)
</p>
<p>
Now, we’re going to use Remote Desktop Protocol (RDP) to connect to the virtual machine using its IPv4 address.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/970e440c-05ba-430f-8142-d08b3cfec2ec)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/7607ba3c-2c67-48c8-b891-9ec016421a14)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/a1796c37-9563-4363-9b10-676c06948290)
![image](https://github.com/user-attachments/assets/d4413cf4-ce4b-4bcd-9b9f-80cbc6471325)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/d921d00b-1536-4642-a5e3-2e4199930986)
![image](https://github.com/user-attachments/assets/7da7bee9-73cd-4624-a1f1-40382105ece4)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/50c2d040-66e4-4f1f-85cb-514f92e1fc4a)
![image](https://github.com/user-attachments/assets/9347d20a-6ee0-48c1-b57c-04a1fde11788)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/ab6bd7f7-6e80-4ccf-b2e4-5f87cee67cbc)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/4488f474-94d0-40e6-9ffd-28a1eb856577)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/32727eb2-ef29-402b-b602-ea995cbf3f9f)
![image](https://github.com/user-attachments/assets/0ac73c58-84ea-4866-a33f-620f1c1e1899)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/73aa6c4b-1d1f-4562-9299-874861ce29a3)
![image](https://github.com/user-attachments/assets/6d178302-5dae-4b2f-a709-14aa3ee26015)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/059d0556-56e8-4491-82bc-6e191e86c253)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/e0334842-8ab5-490f-a1ea-a740e34b7177)
</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/250c696d-6d00-4583-88d8-98e01209eab6)
![image](https://github.com/user-attachments/assets/171542a4-31f7-4753-8975-b8c0bdf34fc8)
![image](https://github.com/user-attachments/assets/5c8281be-f553-4eb1-b284-3b5e7740130a)

</p>
<p>
Next, we connect to the domain controller (DC-1) using Remote Desktop (RDP). Once logged in, we disable the firewall for the domain, private, and public network profiles. This ensures that Client-1 can successfully ping DC-1’s private IP address later in the tutorial without any issues.
</p>
<br />


![image](https://github.com/user-attachments/assets/77839da6-d0b5-43ad-b246-febdc0c3fefe)
![image](https://github.com/user-attachments/assets/5f9d9a78-7b74-41d6-a626-9b2772e8c04c)
