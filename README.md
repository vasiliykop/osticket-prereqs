<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Creating Resource group in Azure
- Creating Miscrosoft VM in Azure

<h2>Installation Steps</h2>

<p> 1. Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
* World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
<p/>
<p>
<img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/00c3c82d-65ef-4413-b6ff-11031188c8a2"/>
</p>

<br/>

<p>
  2 .AND IIS Management Console
* Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console
</p>

<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/064298d0-04d6-45fc-a72e-94a39e7e5b92"

</p>

<br/>

<p>
  3. From the installation file download and install  PHP MANAGER FOR IIS (PHPManagerForIIS_V1.5.0.msi)
</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/4ba62350-611c-4862-970d-400cb23d828b
">
</p>

<br/>
<p>
  4. From the Installation Files, download and install the Rewrite Module (rewrite_amd64_en-US.msi)

</p>
<br>

<p>  5.Create the directory C:\PHP
<p/>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/25c9d93b-90fc-49db-bf13-dafcbe9f24d3">
</p>
<br/>

<p>
   6. From the Installation Files, download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP
</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/db2a0c34-c73b-490c-ac1d-e6b69f936cc4">
</p>
<br/>

<p>
  7.From the Installation Files, download and install VC_redist.x86.exe.

</p>
<br/>
<p>
  8.From the Installation Files, download and install MySQL 5.5.62 

<p/>  
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/8d5080e8-4ac4-43d2-8040-3529f555fb02">
</p>
<br/>

<p>
  9.Open IIS as an Admin

</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/c1528b2c-020a-43a7-8f48-3dd4ad46989a">
</p>
<br/>

<p>
  10.  Register PHP from within IIS
</p>
<p>
  <img scr="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/ead28012-65ac-46a8-9c3d-68ef59c755fd">
</p>
<br/>

<p>
  11.Reload IIS (Open IIS, Stop and Start the server)
</p>
<br/>
<p>
  12.Install osTicket v1.15.8
</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/9b54407a-f3bb-49e6-b63d-565b7ba43c99">
</p>
<br/>

<p>
  13.Reload IIS (Open IIS, Stop and Start the server)
</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/17e4f8a3-014e-4624-ac7c-8886cdb314a6">
</p>
<br/>

<p>
14. Rename Os ticket

</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/dc857764-151a-46ad-ae73-ca15bf9b7cd9">
</p>
<br/>

<p>
  15. Assign Permissions: ost-config.php
</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/c7cd2f2b-ae37-4a00-a44c-a96086200bce">
</p>
<br/>

<p>16. Continue Setting up osTicket in the browser
</p>
<p>
  <img src="(https://github.com/vasiliykop/osticket-prereqs/assets/170582503/3bee662e-57fa-4ce1-8d1b-334c814c2637">
</p>
<br/>
<p>
  17From the Installation Files, download and install HeidiSQL.

</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/cde1f47f-56fc-4d16-98c7-8796e853f22f">
</p>
<br/>
<p>
  18Continue Setting up osticket in the browser
</p>
<p>
  <img src="https://github.com/vasiliykop/osticket-prereqs/assets/170582503/06dd5aac-dcd1-4d5c-8c3e-13d04fb6b1b3">
</p>
