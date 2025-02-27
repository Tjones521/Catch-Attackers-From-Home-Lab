<h1>Implementing a SOC and Honeynet in Azure</h1>


<h2>Description</h2>
I set up a basic home SOC in Azure from scratch. Using a free Azure subscription, we walk through creating a virtual machine (VM), opening it to the internet as a honeypot, and forwarding logs to a central repository. We then integrate Microsoft Sentinel to analyze real-world attack data..
<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure Virtual Machine</b> 
- <b>Microsoft Sentinel(SIEM)</b>
- <b>Log Analytics</b> 
- <b>JSON</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Honey Pot Map: <br/>
<img src="https://i.imgur.com/1vdo6bm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Computer Components that go with the Cloud:  <br/>
<img src="https://i.imgur.com/m1aTltL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Turning off Firewall in Virtual Machine: <br/>
<img src="https://i.imgur.com/0S3LGuv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ping Virtual Machine to see if it has Internet Access:  <br/>
<img src="https://i.imgur.com/9N5UHUw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Putting Wrong Password in for Log:  <br/>
<img src="https://i.imgur.com/LzlYzLz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Log:  <br/>
<img src="https://i.imgur.com/KyylMrK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Log to Sentinel:  <br/>
<img src="https://i.imgur.com/5mrgetw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Windows Security Event Installed:  <br/>
<img src="https://i.imgur.com/4BQwxUm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Forward Logs:  <br/>
<img src="https://i.imgur.com/1jyj2sU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Table Logs on Virtual Machine Forwarded:  <br/>
<img src="https://i.imgur.com/ugX6FIh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filter Through the Logs:  <br/>
<img src="https://i.imgur.com/47xgs0b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filter the Last Five Minutes:  <br/>
<img src="https://i.imgur.com/i7zSiol.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Watchlist Query:  <br/>
<img src="https://i.imgur.com/BShcHnC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Geo List Query to Find Attacker Information and Location:  <br/>
<img src="https://i.imgur.com/kctVNLF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visual Map of Attackers Location:  <br/>
<img src="https://i.imgur.com/9wWSHRX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
