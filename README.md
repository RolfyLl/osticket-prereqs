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
<img src="https://i.imgur.com/8IXa8Sl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next to download was the Rewrite Module Software this allows me to o perform URL manipulation tasks.

</p>
<br />

<p>
<img src="https://i.imgur.com/xDlxdEz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this section of the Installation process i created a Directory in the C:\ Drive Called PHP this was to setup the installion of the PHP 7.3.8 after i extract the file when it finished downloading and unzipped it into the C:\.
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DUvZhB3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next i downloaded VcRedist downloads the supported (and unsupported) Redistributables, for local install, gold image deployment or importing as applications into the Microsoft Deployment Toolkit or Microsoft Endpoint Configuration Manager, or other solutions including Microsoft Intune.
</p>
<br />

<p>
<img src="https://i.imgur.com/NtJ5XEf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here you can see i downloaded My SQL server 5.5 MySQL is a tool used to manage databases and servers, so while it's not a database, it's widely used in relation to managing and organising data in databases. The configuration i used were 

  - Typical setup
  - Standard Configuration

<br />

<p>
<img src="https://i.imgur.com/Hf8aCuT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here i opened IIS as an Admin and registered PHP within IIS. Lastly i restarted the server.
<br />

<p>
<img src="https://i.imgur.com/QZIyYzb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is Finally the part were i downlaod OsTicket system. 

  - Extract and copy “upload” folder to c:\inetpub\wwwroot
  - Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

Notice they were some extensions are not enabled yet. For this i go back into IIS PHP Manager Click “Enable or disable an extension”
  
  - Enable: php_imap.dll
  - Enable: php_intl.dll
  - Enable: php_opcache.dll

</p>
<br />

<p>
<img src="https://i.imgur.com/2dRIQcM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For this Section i setup the Name of the Help desk and setup the default user names and user emails.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
