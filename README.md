<p align="center">
  
  ![image](https://github.com/user-attachments/assets/b9542394-d8f1-4500-8e39-71bd2977ba07)  

</p>

<h1>Proton VPN - Installation</h1>
This tutorial outlines the step-by-step process for installing Proton VPN to ensure secure and private internet access.<br />

<h2>Environments and Technologies Used</h2>

- Proton VPN (Virtual Private Network)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Procedures</h2>

- Set up a virtual machine in Azure and access it via Remote Desktop.
- Register for Proton VPN and install the application.
- Connect to the VPN and verify it’s working.
- Compare and analyze the differences between using a VPN and a regular connection.

<h2>Installation Steps</h2>

<p>

![image](https://github.com/user-attachments/assets/cd61193f-11d3-4e0d-b12e-1a84adfa186f)

</p>
<p>

![image](https://github.com/user-attachments/assets/8a9d5b91-8e12-4822-9e0b-806a834e7bd9)

</p>
<p>
  
I set up a virtual machine in Microsoft Azure, selecting the appropriate configuration for my needs. After provisioning, I enabled remote access and securely connected to the VM using its public IP address through Remote Desktop Connection, entering my credentials to start the remote session.

</p>
<br />

From my personal computer, I visited whatismyipaddress.com to record details such as my IP address, ISP, city, region, and country. I then did the same on the virtual machine (VM) — first without a VPN connection, and then with a VPN enabled — to observe how the IP address and location information changed when using a VPN.

![image](https://github.com/user-attachments/assets/96fe5322-e520-484a-a2fc-bc5209c2c46c)

This image is from my VM from Canada Central with a non-VPN connection.


<p>

![image](https://github.com/user-attachments/assets/37897ab9-35b6-40e6-921d-4215af21bdaf)

Next, I will go to https://account.protonvpn.com/signup?plan=free&language=en and sign up for Proton VPN, downloaded  it, and check for my Go-data 

</p>
<p>
<img src="https://i.gyazo.com/1f21aed85f3704d3255a63da30ff97cf.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/6b8b102cc627ee5e681de36da45d035a.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
After setting up and logging onto the virtual machine (VM), I proceeded to sign up for a Proton VPN account. Following the account creation, I downloaded and installed the Proton VPN client on the VM. The installation process was straightforward, and I ensured the client was properly installed before proceeding.
</p>
<br />

<p>
<img src="https://i.gyazo.com/939f6b5ea4d7b738479c305abc2f3f86.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/3ab93880b73d4b6eb59633425e15ff51.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/5ec1597a49d3c1803f349bab2d67b114.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
To establish a baseline, I visited whatismyipaddress.com on the VM to record its original IP address, ISP, and location. Afterward, I connected to a Proton VPN server located in Japan. Once the VPN connection was established, I revisited the same website and observed the changes: the IP address, ISP, and location had all shifted to reflect the Japanese server, confirming that the VPN was working properly.
</p>
<br />

<p>
<img src="https://i.gyazo.com/bcbfd57da64cb9229d84d12f7c1b69d9.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/90f7f7e3939252de6d708b2e843bc0b8.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
Finally, I conducted a practical test by opening Bing on the virtual machine. I searched for the term “Disney” both while connected to the VPN and again after disconnecting from the VPN. I observed that, while connected to the Japan server, the search results were tailored to the region (with Japanese language content and region-specific results). When disconnected, the search results reverted to the standard English version, indicating that the VPN connection influenced the language and regional search results.
</p>
<br />
