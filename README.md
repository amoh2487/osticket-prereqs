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

- PHP Manager for IIS installation
- URL Rewrite Module for IIS installation
- PHP 7.3.8 Folder Download
- Microsoft Visual C++ for IIS installation
- MySQL Server 5.5 for IIS installation
- HeidiSQL for IIS installation

<h2>Installation Steps</h2>

<p>
</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/90f5b445-ad45-4800-94d0-82afe67e817c)

  
Here, we made a virtual machine in Azure studios in order to connect to our ticketing system on Remote Desktop Connection and to also connect to our installation applications while connecting to the ticket itself.
</p>
<br />

<p>

</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/d992b493-0924-4a04-88d4-17cc51d42b94)

  
After creating our virtual machine and connecting/logging in to our Remote Desktop Connection, we anbled the CGI feature under Application Development Feature; and after that step was completed, we go to a search engine and type 127.0.0.1 which activates and installs our Internet Information Services to ultimately connect to our ticketing system.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/79abf9ff-61fc-4018-a85c-b906eff88670)

  
After we made sure our Internet Information Services was working, we went ahead and installed the PHP Manager for IIS and is one of the required software to install to use/connect our ticketing system.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/dee7c4a2-3c7b-4ed2-aa7f-848468e5fd2b)


After PHP Manager for IIS was successfully installed, we next installed the Rewrite Module for the next required software to connect to our ticketing system.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/1119946c-92d1-45f0-8d5f-207655b64705)

After installing the Rewrite Module, we downloaded the PHP 7.3.8  folder since in this folder we have all of our files/documents to connect to our ticket system because without anything like documents attached to the ticketing system, we cannot access the ticketing system at all.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/17238d93-6221-4eec-992f-36f0becef2d5)

Once the PHP 7.3.8 folder was all done and downloaded successfully, the next software installation of VC_redist.x86.exe is required for our ticketing system since these software allows us to to use both C and C++ tools.
</p>
<br />

<p>
<p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/036a1ea0-b270-4e87-a638-dd198768ed1f)

Once VC_redist.x86.exe was successfully installed, we went ahead and installed MYQSL 5.5.62 since MYSQL provides a database management system to connect our own data to the data of the ticketing system.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/osticket-prereqs/assets/148664179/bdac6bbf-337e-4945-8ea8-05faea0a6924)

After MYSWL 5.5.62 was sucessfully installed to provide database management from our own data to the ticket system, we next downloaded HeidiSQL since HeidiSQL lets us administer our data to the ticketing system and lets us manipulate/change anything on the ticketing system. Lastly, since all of the previous required softwares have downloaded/installed successfully, we can now go and connect to our ticketing system once and for all.
