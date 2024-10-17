<h1>Setting up an SSH Honeypot</h1>


<h2>Description</h2>
In this project, we will set up a Cowrie SSH honeypot to capture and analyze SSH-based intrusion attempts on a network. Utilizing Docker on a Kali Linux environment, Cowrie will be deployed to act both as a medium and high-interaction honeypot. This setup will emulate a UNIX system, meticulously logging SSH access attempts and interactions. By the project's conclusion, we aim to establish a robust honeypot system that will provide deeper insights into network security threats, enabling the observation of attacker behaviors and tactics in a controlled environment.<br />


<h2>Languages and Utilities Used</h2>


- <b>SSH</b>
- <b>Docker</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b> 

<h2>Takeaways</h2>

- <b>Honeypot Deployment and Operations</b>: Mastered the setup and management of the Cowrie honeypot within a Kali Linux environment on Oracle VirtualBox, enhancing skills in deploying and maintaining medium to high interaction honeypots to simulate UNIX systems and SSH/Telnet proxies.


- <b>Attack Simulation and Network Security Proficiency</b>: Gained practical experience in simulating attack scenarios using the Cowrie honeypot, which improved understanding of attacker tactics and techniques. This experience has been instrumental in developing strategies to identify and respond to cybersecurity threats effectively.

- <b>Technical Skills Enhancement in Docker and Virtualization</b>: Advanced technical skills by integrating Docker with the Cowrie honeypot deployment, demonstrating the ability to manage complex security setups using containerization and virtualization technologies for robust cybersecurity defense mechanisms.


<h2>Program walk-through:</h2>

<p align="center">
Initialization of the cowrie honeypot: <br/>
<img src="honeypot initialization 1.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="honeypot initialization 2.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running an nmap scan to detect the honeypot server, with open access being identified through port 2222:  <br/>
<img src="nmap test scan.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log analysis: <br/>
<img src="access into ssh server.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Custom query for nmap: <br/>
<img src="fake server contents.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<br />
<br />
Dashboard containing security events:  <br/>
<img src="honeypot log.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
