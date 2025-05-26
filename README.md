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

Next, I went to https://account.protonvpn.com/signup?plan=free&language=en and signed up for Proton VPN.

![image](https://github.com/user-attachments/assets/97768f0e-d2ce-4d91-8277-1d6ee62bdb41)

I signed in. 

![image](https://github.com/user-attachments/assets/cc5cbc9e-0cd6-41e8-9f4b-b9ccda52f107)

After signing in, I clicked on download and chose the operating system that applied to me. 

![image](https://github.com/user-attachments/assets/3747f82f-7aab-458f-ba3f-6cfbb3703df1)

I proceeded to download and install the VPN client, which is the software that will create a secure connection between my computer and the VPN server. 

![image](https://github.com/user-attachments/assets/dc0b4064-c3a5-41f0-9001-51be86bc24d7)

The installation was simple, and I verified that the VPN client was correctly set up before moving forward.

![image](https://github.com/user-attachments/assets/2fdea2a8-3e96-4ca6-a0f8-7a84c99b8709)

I clicked on the country "Nigeria," but it prompted me to pay and automatically brought me to the Netherlands. So, what just happened here is that my VM connected to a random server in the Netherlands. 

![image](https://github.com/user-attachments/assets/1b23b95f-3f6c-4e30-887c-05f92abe77f8)

I went to this website  https://whatismyipaddress.com/ on the internet while connected to the VPN, my traffic appeared to originate from the VPN server located in the Netherlands, making it seem as though I'm browsing from that country instead of my actual location.

</p>
<p>

![image](https://github.com/user-attachments/assets/5aed9438-511c-417a-b4a6-faf2ebedc1ed)

To test the VPN connection, I tried browsing the internet and visited www.Disney.com. Because my VPN was connected to a server in the Netherlands, the website automatically detected my virtual location and displayed the content in Dutch, the official language of the Netherlands.

![image](https://github.com/user-attachments/assets/beeee60c-8dd6-4077-8ec6-8cbb61987ea9)

This is the pictorial summary of everything I did. I connected from my personal computer to an Azure Virtual Machine (VM) using Remote Desktop Protocol (RDP). On the VM, I installed and connected to ProtonVPN, routing all internet traffic through a Netherlands VPN server. When the VM accesses public websites like whatismyipaddress.com, it appears to be browsing from the Netherlands. This setup demonstrates how VPNs can change one's visible IP address and location.


</p>
<p>

