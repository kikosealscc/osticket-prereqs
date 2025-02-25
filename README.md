<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

-  ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/LOzmM5ZjKi0?si=fG4fzoh03PL70o1l)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11 Pro </b> (23H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Install Web Platform Installer
- Install PHP Manager
- Install MySQL
- Install C++ Redistributable
  

<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/e8dc3841-e1e0-4467-829a-2442eb3f0a7d)


<p>

Click start > Control Panel > Programs > Turn Windows Features on > Check box on Internet information services > Expand the box to see World Wide Web Services > World Wide Web Services -> Application Development Features -> [X] CGI > Ok > Web Server will start installing > Close > Open tab and type:  IP address to see Internet Information Services
  
</p>
<br />

![image](https://github.com/user-attachments/assets/b836e8f5-e2de-4b88-91e6-e9354c94524c)



</p>
Create the directory C:\PHP - Open File Explore > Make folder on C:Drive > PHP Folder > php-7.3.8…file > Browse to C: Drive > PHP Folder > Extract All


</p>
<br />

<p>


![image](https://github.com/user-attachments/assets/a125817a-607a-42a1-8afc-12930673a0d9)



</p>


From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe. Click VC_restrx86 (highlighted in box below) > Click Yes



<br />


</p>

![image](https://github.com/user-attachments/assets/83d54d25-8c04-4eb0-bd61-9b5ba2c94237)


</p>

From the “osTicket-Installation-Files” folder > install MySQL 5.5.62 (mysql-5.5.62-win32.msi) 
Typical Setup > Launch Configuration Wizard (after install) > Standard Configuration > Username: root > Password: root


</p>
</p>



![image](https://github.com/user-attachments/assets/1f48238a-9ebe-4558-80ac-934ec9667d6e)

</p>
</p>

From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe






