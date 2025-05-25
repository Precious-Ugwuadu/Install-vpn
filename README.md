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
<img src="https://i.gyazo.com/f21bb85ab7219dcd16c2e0cf8a4b0690.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/67c0002f8368bb79dc0c0cd886aaf479.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
I began by creating a new virtual machine (VM) within Microsoft Azure, carefully selecting the configuration based on my desired specifications. Once the VM was successfully provisioned, I ensured it was ready for remote access. To log onto the VM, I used Remote Desktop Connection to securely connect, entering the necessary credentials to establish the session.
</p>
<br />

<p>
<img src="https://i.gyazo.com/f563212d7120ee0ed2f48402dc10bff8.png" height="80%" width="80%" alt="Configure VPN Steps"/>
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
