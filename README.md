<h1>Cyber Threat Intelligence: Analysis of APT 12</h1> 

<h2>Background</h2> 
APT12 is a state-sponsored advanced persistent threat (APT) group that is based in China. The group's primary objective is speculated to be espionage, and they have targeted a wide range of industries, including defense, energy, aerospace, technology, government, and media. APT12 has mainly targeted Japan, Taiwan, and the United States.  
<br /> 
<br />
By understanding APT12's tactics, techniques, and procedures (TTPs), individuals and organizations can develop more effective security practices such as patching known vulnerabilities in their software and operating systems, implementing email security solutions, and monitoring networks and systems for suspicious activity. 
<br />
<h2>Diamond Model of Intrusion Analysis</h2>
<img src="https://i.imgur.com/OZMRcVn.png" height="100%" width="100%" alt="Import Module"/>
<h3>Adversary</h3> 
APT12 also goes by the names DynCalc, Numbered Panda, DNSCALC, and IXESHE. They have mainly targeted Japan, Taiwan, and the United States. Their target industries are the aerospace, defense, and energy industries. Furthermore, they have also targeted government and media-outlets, such as the New York Times. APT12 is known for their sophisticated and targeted attacks. 
<h3>Victims</h3> 
One of APT12's most famous attacks was against the New York Times in 2012. In this attack, APT12 compromised the passwords and personal data of many New York Times employees, including the bureau chief and the South Asia bureau chief of New York Times. APT12 has also sent spear phish emails to a Taiwanese government ministry. 
<h3>Capabilities</h3> 
APT12 has used a variety of methods for their attacks, such as backdoors to gain initial access to a victim's system, steal data, and maintain persistent access to the system. Backdoors can be installed on a system through a variety of methods, such as phishing attacks, malware infections, and software vulnerabilities. WATERSPOUT is one of the backdoor’s implemented by APT12, which is an HTTP backdoor that communicates to the command and control (C2) server. RIPTIDE and HIGHTIDE are two more of APT12’s backdoors. 
<br /> 
<br />
DNS calculation is another method APT12 uses to gain access to the command and control (C2) port. This is done by multiplying the first two IP address octets, and then adding the third octet to that result. This process can be used to steal data, install additional malware, or launch other attacks against the victim's system.
<h3>Infrastructure</h3> 
APT12 uses a variety of infrastructure to launch and support their attacks. A common attack method of APT12 is exploiting bugs in software to gain leverage of systems and networks. APT12 has exploited many Microsoft Office, Adobe Reader, and Flash vulnerabilities. APT12 has also used a variety of C2 servers, including blogs, WordPress sites, and cloud storage providers.
<h2>Lockheed Martin Cyber Kill Chain</h2>
<img src="https://i.imgur.com/xe4RG3h.png" height="100%" width="100%" alt="Import Module"/>
The Lockheed Martin Cyber Kill Chain is a model that depicts and describes the steps involved in a cyberattack. The seven steps of the APT12 kill chain are:
<br /> 
<br />
<strong>Reconnaissance:</strong> APT12 gathers information about its target, such as its IP address, domain names, and email addresses. For more targeted spear phishing attacks, they gather information on high-profile individuals.
<br /> 
<br />
<strong>Weaponization:</strong> APT12 creates a malicious payload that it will use to exploit a vulnerability in the target's system. These malicious payloads typically come in the form of vulnerabile software, such as Microsoft Office, Adobe Reader, and Adobe Flash. 
<br /> 
<br />
<strong>Delivery:</strong> APT12 delivers the malicious payload to the target, typically via phishing emails, or through a malicious website such as WordPress. 
<br /> 
<br />
<strong>Exploitation:</strong> APT12 exploits vulnerabilities in software and DNS calculation to gain access to the target’s system. DNS calculation is used to gain access to the command and control (C2) port. 
<br /> 
<br />
<strong>Installation:</strong> The malicious payload is then installed on the target's system, which is used to install a backdoor. 
<br /> 
<br />
<strong>Command and control (C2):</strong> APT12 communicates with the target's system and issues commands to maintain persistent access. 
<br /> 
<br />
<strong>Actions on objectives:</strong> APT12 carries out its objectives using the command and control (C2) server to conduct espionage and gather sensitive data on their targets. 
<h2>MITRE ATT&CK Framework</h2>
To view the MITRE ATT&CK Navigator for APT12, refer to the following link: https://mitre-attack.github.io/attack-navigator//#layerURL=https%3A%2F%2Fattack.mitre.org%2Fgroups%2FG0005%2FG0005-enterprise-layer.json
<br /> 
<br />
<img src="https://i.imgur.com/IVrCahD.png" height="55%" width="55%" alt="Import Module"/>
<br /> 
<br />
<strong>ID:</strong> T1566.001
<br /> 
<br />
<strong>Technique:</strong> Phishing
<br /> 
<br />
<strong>Subtechnique:</strong> Spearphishing Attachment
<br /> 
<br />
<strong>Tactic:</strong> Initial Access
<br /> 
<br />
<strong>Procedure:</strong> APT12 sends targeted emails with malicious Microsoft Office documents and PDFs attached. These file formats are effective because they are commonly used in business and government settings. Once the attachment is opened, malicious code is executed that can infect the victim's computer with malware. The malware can then be used to gain remote access to the victim's computer.
<br /> 
<br />
<strong>Mitigations:</strong> Implement robust antivirus solutions, anti-spoofing and email authentication technologies, and provide extensive user training.
<br /> 
<br />
For more information on spearphishing, refer to the following link: https://attack.mitre.org/techniques/T1566/001/
<br /> 
<br />
<img src="https://i.imgur.com/ZUQMEMF.png" height="55%" width="55%" alt="Import Module"/>
<br /> 
<br />
<strong>ID:</strong> T1568.003
<br /> 
<br />
<strong>Technique:</strong> Dynamic Resolution 
<br /> 
<br />
<strong>Subtechnique:</strong> DNS Calculation
<br /> 
<br />
<strong>Tactic:</strong> Command and Control
<br /> 
<br />
<strong>Procedure:</strong> APT12 gains access to the command and control (C2) port by using DNS calculation. An example of how APT12 has done this is by multiplying the first two IP address octets and then adding the third octet to that result. This technique makes it more challenging for security researchers to detect and block the malware.
<br /> 
<br />
<strong>Mitigations:</strong> Monitor the network traffic for unusual DNS requests and implement a firewall to block incoming connections to unusual ports. 
<br /> 
<br />
For more information on DNS calculation, refer to the following link: https://attack.mitre.org/techniques/T1568/003/
<br /> 
<br />

<h2>Summary</h2>
<h2>Sources</h2>
APT12. APT12, IXESHE, DynCalc, Numbered Panda, DNSCALC, Group G0005 | MITRE ATT&amp;CK®. (n.d.). Retrieved February 25, 2023, from https://attack.mitre.org/
<br /> 
<br />
Meyers, A. (2017, October 11). Software Supply Chain Attacks on the Rise, Undermining Customer Trust. crowdstrike.com. Retrieved February 25, 2023, from https://www.crowdstrike.com/ 
<br /> 
<br />
Moran, N., &amp; Oppenheim, M. (2022, November 28). Darwin’s Favorite APT Group. Mandiant. Retrieved February 25, 2023, from https://www.mandiant.com/

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
