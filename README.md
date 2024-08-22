# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>


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

<h2>Step 1 </h2>
  The first stage was to create a virtual machine in Azure. I created a Resource Group then created a Windows 10 virtual machine with 2 virtual CPUs so that it had sufficient resources. This also allowed me to create a virtual network.

![Creating DC-1 copy](https://github.com/user-attachments/assets/45986734-6b76-4601-ad62-9583139061e4)

</p>


<p>

</p>
<br />

<p>



<p>
<h2> Step 2</h2>
The next stage was to enable Internet Information Services on the virtual machine. Click on start and look and type ISS and   IIS is a crucial component for running osTicket on a Windows server. It provides the necessary web server environment for the application to function properly and interact with users through the internet. I turned CGI, Common HTTP Features and IIS Management Console. To enable IIS with CGI Control Panel > Programs and Features > Turn Windows Features on or off > World Wide Web Services > Application Development Features > CGI (check) Expand Internet Information Services. To enable IIS Management Console Internet Information Services > Web Management Tools > IIS Management Console
</p>
<br />


<p>

![Configuring ISS](https://github.com/user-attachments/assets/26df7b13-857c-42bb-bb9e-7f8be25a6235)

![Internet information service](https://github.com/user-attachments/assets/ae26d97e-91dc-4fe8-bec9-9e7f1d953cda)  ![check cgi](https://github.com/user-attachments/assets/67274c7e-21a5-4563-bc4a-b92b6ade5533)           
![Internet information service](https://github.com/user-attachments/assets/52adb8ce-038b-48b1-9c49-bca2da8931c1)![making sure all checked](https://github.com/user-attachments/assets/01f51c44-5944-47e4-8e75-7b40671bfc85)












</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
