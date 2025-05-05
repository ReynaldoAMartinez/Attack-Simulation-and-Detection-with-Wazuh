Attack-Simulation-and-Detection-with-Wazuh


<h2>Description</h2>
Simulating an end-to-end Cyber attack and implementing different detections throughout the life cycle to show how a Cyber attack is detected
<br />


<h2>Environments Used </h2>


- <b>Virtual Box</b>
- <b>Windows Server 2025</b>
- <b>Windows 11 Enterprise</b> 
- <b>Ubuntu Server 22.04</b>
- <b>Ubuntu Desktop 22.04</b>
- <b>Wazuh</b>
- <b>Security Onion</b>
- <b>Postfix</b>


<h2>Program walk-through:</h2>

The first step was to build an Enterprise Network with the following configuration:

![Alt Text](https://github.com/ReynaldoAMartinez/Attack-Simulation-and-Detection-with-Wazuh/blob/main/Project-X%20(3).png))


A Windows Server 2025: Used as the directory services server, acting as the central hub for network connections.
A Windows 11 Enterprise: Used to simulate a business user.
An Ubuntu Desktop 22.04: Used to simulate an enterprise software development environment.
A Security Onion: Used to detect, investigate, and respond to network threats and incidents.
An Ubuntu Server 2022: Used as the email server.
Kali Linux: Used to do the attack simulation against the enterprise network.


