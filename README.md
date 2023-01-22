<h1>SIEM Homelab</h1>

<h2>Description</h2>
In this Homelab I created a windows machine virtual functioning as a honeypot , to allow me to observe live attack from threat actors accross the world . I was able to accomplish this using Microsoft azure to setup Azure Sentinel (SIEM).
<br />


<h2>Languages and Utilities Used</h2>

- <b>Powershell</b> 
- <b>Microsoft Azure</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b> Mac OS 10</b>

<h2>Lab walk-through:</h2>


Create a Virtual Machine in Microsoft azure :  <br/>
<img src="https://i.imgur.com/3ye4Fw7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Make Firewall open to all traffic on the internet : <br/>
![image](https://user-images.githubusercontent.com/122640173/213933855-d28bde1f-9c48-47eb-9594-09d21603b10c.png)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Log Analytics Workspace : <br/>
<https://i.imgur.com/Ec4MVpK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
