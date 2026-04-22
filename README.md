<h1>Windows Server Infrastructure Lab: SQL Server & SSMS Deployment</h1>

<h2>Description</h2>

This project demonstrates a hands-on IT infrastructure lab focused on building and configuring a Windows Server 2022 environment. The lab simulates real-world system administration tasks including virtual machine setup, network configuration, server hardening, and SQL Server deployment.

In this lab, I configured a static IP address, adjusted security settings, and installed SQL Server along with SQL Server Management Studio (SSMS). I then successfully connected to the SQL instance to verify full functionality. This project highlights practical experience in system administration, networking, and database management within a Windows Server environment.

<br />

<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2022</b>
- <b>Oracle VirtualBox</b>
- <b>SQL Server 2025 Developer Edition</b>
- <b>SQL Server Management Studio (SSMS)</b>
- <b>Windows Networking (IPv4 Configuration)</b>

<br />

<h2>Environments Used</h2>

- <b>Windows Server 2022 Virtual Machine</b>
- <b>VirtualBox Internal Network (intnet)</b>

<br />

<h2>Lab Walk-through:</h2>

<p align="center">

Create and Configure Virtual Machine<br/>
<i>Set up a virtual machine in VirtualBox and attach the Windows Server 2022 ISO.</i><br/>

<img src="step-01-vm-network-settings.png" width="100%"/>
<img src="step-01-iso-mounted.png" width="100%"/>
<br/><br/>

Install Windows Server 2022<br/>
<i>Complete installation and select Desktop Experience for GUI-based management.</i><br/>

<img src="step-02-install-now.png" width="100%"/>
<img src="step-02-os-selection.png" width="100%"/>
<br/><br/>

Initial Login and Setup<br/>
<i>Configure Administrator credentials and log into the server environment.</i><br/>

<img src="step-03-login-screen.png" width="100%"/>
<img src="step-03-set-admin-password.png" width="100%"/>
<br/><br/>

Access Server Manager<br/>
<i>Open Server Manager to begin system configuration and management tasks.</i><br/>

<img src="step-04-server-manager-dashboard.png" width="100%"/>
<br/><br/>

Configure Network Adapter<br/>
<i>Navigate to network settings and access Ethernet adapter configuration.</i><br/>

<img src="step-05-network-settings.png" width="100%"/>
<br/><br/>

Configure Static IP Address<br/>
<i>Assign a static IPv4 address, subnet mask, gateway, and DNS for network communication.</i><br/>

<img src="step-06-01-ethernet-status.png" width="100%"/>
<img src="step-06-02-ethernet-properties.png" width="100%"/>
<img src="step-06-03-IPv4-configuration.png" width="100%"/>
<br/><br/>

Configure Security Settings<br/>
<i>Disable Internet Explorer Enhanced Security Configuration (IE ESC) to allow downloads and web access.</i><br/>

<img src="step-07-01-IE-ESC-Disabled.png" width="100%"/>
<img src="step-07-02-local-server-verification.png" width="100%"/>
<br/><br/>

Rename Server and Join Domain<br/>
<i>Rename the server and configure domain settings using domain credentials.</i><br/>

<img src="step-08--01-computer-name.png" width="100%"/>
<img src="step-08-02-domain-join.png" width="100%"/>
<img src="step-08-03-domain-credentials.png" width="100%"/>
<br/><br/>

Install SQL Server<br/>
<i>Install SQL Server Developer Edition and configure database engine settings.</i><br/>

<img src="step-09-00-sql-installer-file.png" width="100%"/>
<img src="step-09-01-sql-installer-launch.png" width="100%"/>
<img src="step-09-02-sql-installation-center.png" width="100%"/>
<img src="step-09-03-sql-feature-selection.png" width="100%"/>
<img src="step-09-040sql-database-configuration.png" width="100%"/>
<br/><br/>

Install SQL Server Management Studio (SSMS)<br/>
<i>Download and install SSMS to manage SQL Server instances.</i><br/>

<img src="step-10-01-SSMS-Download-Page.png" width="100%"/>
<img src="step-10-02-SSMS-Launch.png" width="100%"/>
<br/><br/>

Connect to SQL Server<br/>
<i>Connect to the SQL Server instance using SSMS and verify successful deployment.</i><br/>

<img src="step-11-01-ssms-connection-window.png" width="100%"/>
<img src="step-11-02-ssms-connected.png" width="100%"/>
<br/><br/>

</p>

<h2>Skills Demonstrated</h2>

• Windows Server Administration  
• Network Configuration (Static IP)  
• Virtualization (VirtualBox)  
• SQL Server Installation and Configuration  
• Database Management with SSMS  
• System Troubleshooting  
• Enterprise Infrastructure Setup  
