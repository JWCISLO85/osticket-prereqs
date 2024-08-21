# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Created Virtual Machine in Azure.
- Enabled IIS in Windows with CGI and common HTTP features.
- Enabled IIS Managent Console
- Installed PHP Manager for IIS
- Installed Rewrite Module
- Installed Visual C++
- Installed MYSQL Database
- Installed OSTicket and configured

<h2>Installation Steps</h2>



![Creating DC-1 copy](https://github.com/user-attachments/assets/45986734-6b76-4601-ad62-9583139061e4)

</p>


<p>
The first stage was to create a virtual machine in Azure. I created a Resource Group then created a Windows 10 virtual machine with 2 virtual CPUs so that it had sufficient resources. This also allowed me to create a virtual network.
</p>
<br />

<p>





</p>
<p>
The next stage was to enable Internet Information Services on the virtual machine. This is because IIS  is a crucial component for running osTicket on a Windows server. It provides the necessary web server environment for the application to function properly and interact with users through the internet.I also had to check IIS Mangement Console by going to Interney
</p>
<br />

<p>
![Configuring ISS](https://github.com/user-attachments/assets/6cd25cdd-fc71-498f-b03d-3b9b08e58e5e)
![check cgi](https://github.com/user-attachments/assets/4ffe5e40-0b71-4e9d-b000-fd8fd42d7181)
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
