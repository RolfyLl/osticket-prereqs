<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- My SQL/ Heidi SQL
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create virture machine on Azure
- Install/ enable IIS in windows with CGI and common
- HTTP features
- Download and install VC_redist
- Download and install MySQL
- Download and install Heidi SQl

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/h2tzhCg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin with i created a Virtual Machine using Microsoft Azure. To setup the enviroment where i will be doing the lab. Here i will setup the Osticket sytem. While doing this part of the lab i gained hands on experience using Azure on of the leading Cloud storages servies today. I Connected to the VM using Remote Desktop. I gained experience both as a Adminstrative and as a user. I was also exposed to all parts of the ticketing system such as 
  
  - Ticket properties
  - SLAs
  - Departments
  - Permissions
  - Users

    
</p>
<br />

<p>
<img src="https://i.imgur.com/C7C05L0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this part of the installation process i enabled IIS. Because osTicket runs out of a website we need to configure IIS to be able to Run Osticket. Here i enabled the following Features:

  - Internet Information Services
  - World Wide Web Service
  - Application Development Feutures
  - CGI
  - Common HTTP Features
  - Default Document
  - Directory Browsing
  - HTTP errors
  - HTTP redirection
  - Static content
  - Webdav Publishing

To test that i did it correctly i pinged 127.0.0.1 which to took me to the Internet Information Services Web Site.

</p>
<br />

<p>
<img src="https://i.imgur.com/jS9KCJe.png"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here i downloaded PHP manager which allows me to install, run, and manage PHP versions on a Windows server running the Internet Information Services (IIS) webserver.
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
