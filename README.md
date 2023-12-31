# Installing-and-Utilizing-of-pfSense-Firewall 🛡️🚫

<h2>📚 Introduction</h2>
Welcome back, for this project I will delve into the implementation and utilization of pfSense firewall 🧱. This is an open-source firewall that acts as a protective barrier between your internal network and the internet, allowing you to control and monitor incoming and outgoing traffic. It is also user-friendly which makes it accessible to both beginners and experienced users.

<h2>🛠️ Tools That I Used</h2>

- <b>[VirtualBox🔄-(Download the version for your operating system)](https://www.virtualbox.org/wiki/Downloads)</b>: This is an open-source virtualization platform that allows us to create and manage virtual machines (VMs). For our cybersecurity home lab, I would be using it to simulate diverse operating systems and network configurations within isolated environments.
- <b>[pfSense Firewall 🧱-(Download the AMD 64-bit version)](https://pfsense.org/download/)</b>: With this, I can implement firewall rules, manage network address translation (NAT), set up virtual private networks (VPNs), and perform other security-related tasks.

<h2>🔄💻 Required System Requirement: I use an HP ENVY x360 Laptop (Not the best but it does the job)</h2>

- <b>[🧠 CPU: 13th Gen Intel(R) Core(TM) i7-1355U 1.70 GHz (Anything higher than this will work)]</b>
- <b>[💾 RAM: 16GB (gigabytes) of RAM (I will say 8 GB of RAM or higher will suffice)]</b>
- <b>[📀 Disk: 1TB (Terabyte) (500GB - 1000GB of free disk space will be enough)]</b>
- <b>[🔄 BIOS/UEFI: VT-x, AMD-V, or the equivalent must be enabled in the BIOS/UEFI]</b>
- <b>[🔧 System Type: 64-bit operating system, x64-based processor (⚠️MANDATORY: This is a must)]</b>

<h2>📝 Step by Step Guide To Setting Up pfSense Firewall

- <b>[THIS LINK IS A WELL-DETAILED GUIDE OF THE PROJECT](https://www.youtube.com/live/GUCRDqplwMQ?si=YrEbBZ45ju9DIfwx)</b>

- <b>📝 STEP 1: Download and install VirtualBox from the official website. Follow the installation instructions for your operating system.</b>

- <b>📝 STEP 2: Download the ISO file for the pfSense firewall (You will need to use 7zip file manager to extract the file). Lastly, Follow the video I linked above because the installation is a bit tricky.</b>
<img width="582" alt="Screenshot 2023-12-31 062344" src="https://github.com/IsaacOribamise/Installing-and-Utilizing-of-pfSense-Firewall/assets/154943957/9975c5a5-8f73-4b1b-815b-9b47c8bff692">


- <b>📝 STEP 3: We are then going to access the pfSense Web Interface by entering the LAN IP address in a web browser (mine was 192.168.0.19)</b>
<img width="433" alt="Screenshot 2023-12-29 054509" src="https://github.com/IsaacOribamise/Installing-and-Utilizing-of-pfSense-Firewall/assets/154943957/949cb091-f0ac-44bd-945a-ce29219356ed">

- <b>📝 STEP 4: Log in with the default username: 'admin' and password: 'pfsense' > Then I went through the initial configuration where we would set our hostname, and change the admin password. Lastly just familiarized myself with the pfSense dashboard, which provided an overview of system status and network information.</b>
<img width="911" alt="Screenshot 2023-12-29 000454" src="https://github.com/IsaacOribamise/Installing-and-Utilizing-of-pfSense-Firewall/assets/154943957/818fccfa-fc0d-4a84-8b39-279e1a74e373">


- <b>📝 STEP 5: Performed basic configurations like setting up firewall rules. For this, I created a firewall alias (It is a feature that allows me to create  a named list of IP addresses, networks, or ports that can be referenced in firewall rules.) I then customized the firewall rules to block traffic coming from that certain website.</b>
<img width="886" alt="Screenshot 2023-12-29 041818" src="https://github.com/IsaacOribamise/Installing-and-Utilizing-of-pfSense-Firewall/assets/154943957/806b0afc-327a-40d4-bece-3c6b71719417">


- <b>📝 STEP 6: Performed another basic configuration which was setting up an OpenVPN for a user, this is used for  allowing remote users to connect to a network securely. I navigated to the "VPN" > "OpenVPN" > "Servers." Click on the "Add" button to create a new OpenVPN server, did the regular configuration. Created an OpenVPN user, downloaded and Installed OpenVPN Client, and connected to the OpenVPN Server.</b>
<img width="442" alt="Screenshot 2023-12-29 045024" src="https://github.com/IsaacOribamise/Installing-and-Utilizing-of-pfSense-Firewall/assets/154943957/6a0c8661-e703-431b-b85e-663428a3b10b">


- <b>📝 STEP 7: Lastly, I familiarized and played around with other features for hands-on experience. So keep watch for the next project</b>

<h2>💡 key lessons and takeaways from this project:</h2>

- In this project of setting up and utilizing the pfSense firewall, several valuable lessons were learned that contribute to a better understanding of network security and firewall management. Here are my key takeaways from this project: 
The understanding of how the OpenVPN server works, creating user accounts, configuring the OpenVPN server, and connecting to it through an OpenVPN client shows how businesses use secure communication, especially in remote or off-site scenarios.
The understanding of firewall rules and aliases, helped us control traffic between different  network activities.

<h2> 🤳 Connect with me:</h2>

- Let's connect and share our passion for cybersecurity!
- Feel free to reach out for collaborations, discussions, or just to geek out over the latest exploits. 
- My LinkedIn page is below:

[<img align="left" alt="RichardSaunders | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[linkedin]: https://www.linkedin.com/in/isaac-oribamise/
