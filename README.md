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

- Install/Enabled IIS (Internet Information Services) with CGI
- Installed Web Platform Installer (PHP Manager for IIS)
- Installed C++
- Installed MySQL
- Install osTicket

<h2>Installation Steps</h2>

<p>


![Capture](https://github.com/user-attachments/assets/e3561bb2-cd5d-4c52-8db9-1d6e977a09f3)
 ![image](https://github.com/user-attachments/assets/bd2a756b-d976-462a-a22d-bec8d25103a5)


To enable IIS settings with CGI, I opened up Control Panel in the start menu. Opened "Programs Uninstall Programs"  Turns Windows Features On or Off. I located IIS and enabled it. Next, within World Wide Web services, and Application Development Features, I enabled CGI
</p>![image](https://github.com/user-attachments/assets/44ae28f6-7603-4316-b6bb-a8d43159dcf4)



<p>![image](https://github.com/user-attachments/assets/9d5ac045-74f7-48ff-9948-9d9c56def069)

![image](https://github.com/user-attachments/assets/3505098e-64da-4da2-9edd-205ed39c977d) ![image](https://github.com/user-attachments/assets/f8bfa8bb-2429-49bc-ab4a-d89ef4d008cf) ![image](https://github.com/user-attachments/assets/f81a53b5-d744-453b-9bcf-a6104b91c773) ![image](https://github.com/user-attachments/assets/898cea5d-86e3-4f4d-b17a-2d19f04fce9c)




>PHP is required to run osTicket. Inside of the osTicket installation file, I located the PHP Manager file to open it, agreed to the licensing agreement and followed the proper prompts. The fourth image shows PHP installation being complete and installed. 
</p>
<br />
![image](https://github.com/user-attachments/assets/ae867d54-a81b-4ce9-a89c-9e33b686bfda)

![image](https://github.com/user-attachments/assets/e1cc9bca-9dc9-417d-a6b0-4176d9afb388) ![image](https://github.com/user-attachments/assets/d56dbbaf-cd08-487a-8a49-2a1923825788) ![image](https://github.com/user-attachments/assets/508d2b1f-ac71-4571-970e-90b0c87982cc) ![image](https://github.com/user-attachments/assets/a98e9c68-426c-41de-853b-fa6388702177)










The image above shows the installations of C++. Another dependency for osTicket to work properly. Inside of osTicket installation file, I located the VC redist.x (C++) file. Doubled clicked to open and began following the prompts to allow installation. Installation was successful.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/f0348049-2dce-4904-9672-919c93559af3) ![image](https://github.com/user-attachments/assets/7935f364-c973-4f11-8b57-e53a6551c015) ![image](https://github.com/user-attachments/assets/484f56df-2f2f-4f08-8c34-a7e296ad5a84) ![image](https://github.com/user-attachments/assets/a60c77ce-f900-4c51-aa8e-a5d858793032) ![image](https://github.com/user-attachments/assets/84143dc9-50f6-405a-b356-50064be28b72) ![image](https://github.com/user-attachments/assets/f61de51b-9291-4dfb-a746-f1b0b215d76d)







Next is the installation of MySQL, which is a database that osTicket uses to store all of our data in, such as user accounts and ticketing information. Inside of the osTicket Installation File, I located MySQL file and opened it. Then I began following the prompts to successfully install the file. 
</p>
<br />

<p></p>

![image](https://github.com/user-attachments/assets/c35337d3-f701-41cf-b8be-dc0652ec1f17)   ![image](https://github.com/user-attachments/assets/6f3be922-9224-4a58-84c3-aadf15675531) ![image](https://github.com/user-attachments/assets/6e7f1d53-3bed-41f8-bd25-44da80203cbb) ![image](https://github.com/user-attachments/assets/36874e84-65fc-47db-a899-c4e08e4f6a81)







There are a number of steps involved in the installation of osTicket. After the initial setup pictured above, I had to launch the Configuration Wizard, setup as "standard", and then create Username and Password. More files were uploaded and renamed within the C: drive of File Explorer. Extensions were also enabled. Permissions for access of files within osTicket were configured on the Administration side. The first two images below show osTicket before extensions were enabled. The third image shows the enabled extensions.



![image](https://github.com/user-attachments/assets/b39ec09b-6377-43ac-a4d0-2fb5d75b904b)
![image](https://github.com/user-attachments/assets/ccf5dc28-55c0-460e-a2f4-9419e123da76)
![image](https://github.com/user-attachments/assets/4b0ea7b4-5dd2-4f39-b154-6d04ed24c85c)




The above images show osTicket before and after the prerequisites were enabled. Some features help osTicket to function better, and were necessary for proper functionality.









