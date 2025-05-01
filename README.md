<h1> IntrusionProtection System Lab </h1>

<h2>Description</h2>
In this Intrusion Protection System (IPS) lab, I successfully configured and implemented Snort on the pfSense firewall to enhance network security. After logging into pfSense, I installed and configured the Snort package, integrating my unique "oinkcode" for updates. I also implemented WAN and LAN interfaces, conducted a full Snort scan on a Kali VM, and captured logs of altered events during the scan. The use of hardening methods, such as enabling portscan detection, updating Snort with community rules, and fine-tuning configurations, significantly improved the system's ability to detect and respond to network scans, thereby reducing false positives and strengthening overall threat detection.
<br />

<h2>Languages and Utilities Used</h2>

- <b> pfSense </b> 
- <b> Snort </b>
- <b> Oinkcode </b>
- <b> GVM </b>

<h2>Environments Used </h2>

- <b> Kali Linux VM </b>

<h2>Project walk-through:</h2>
<p align="left">
TEXT. <br/><br/>
  <img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>

  
<h2>Write Up</h2>

<p> Hardening methods played a key role in detecting the scans during the lab. Enabling the port scan allowed Snort to monitor network traffic and flag unusual patterns like rapid port probing. Updating Snort with the latest community rules ensured it could recognize modern scanning techniques, such as those used by tools like GVM. Additionally, fine-tuning configuration settings improved detection accuracy by reducing false positives and focusing on relevant threats. These measures coll ectively enhanced Snort’s ability to effectively identify and log suspicious activities.
</p>
