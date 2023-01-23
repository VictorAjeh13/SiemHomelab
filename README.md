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

<br />
<br />
Create a Log Analytics Workspace : <br/>
<img width="862" alt="Screen Shot 2023-01-22 at 11 48 18 AM" src="https://user-images.githubusercontent.com/122640173/213948693-e9516ed0-9f80-44c0-b24d-e365e7e2e1a0.png">

<br />
<br />

Set up Microsoft Sentinel:  <br/>
<img width="862" alt="Screen Shot 2023-01-22 at 11 48 18 AM" src="https://user-images.githubusercontent.com/122640173/213948855-6e7e03be-a5c0-4197-a5a4-043a5ea3ee76.png">

Get IP Address for Virtual Machine:  <br/>
<img width="702" alt="Screen Shot 2023-01-21 at 4 43 34 PM" src="https://user-images.githubusercontent.com/122640173/213949388-6bc17b98-fe57-4b25-bbab-ab46e16629ab.png">

Use Microsoft Remote Desktop to connect Local machine to Virtual Machine:  <br/>
<img width="604" alt="Screen Shot 2023-01-21 at 4 30 59 PM" src="https://user-images.githubusercontent.com/122640173/213949280-881d68b5-d518-4422-a3eb-afcc1a5ddd84.png">


View Security Events on Virtual Machine :  <br/>
<img width="909" alt="Screen Shot 2023-01-22 at 6 10 05 PM" src="https://user-images.githubusercontent.com/122640173/213950996-a223309b-0985-4c66-ab90-94aa1965fbc6.png">

Configure Firewall Settings in Virtual Machine:  <br/>
<img width="774" alt="Screen Shot 2023-01-22 at 9 29 35 AM" src="https://user-images.githubusercontent.com/122640173/213951486-f71050d1-3aa4-47dd-a1f0-bae0021797a1.png">

Get Geolocation.io API Key <br/>
<img width="753" alt="Screen Shot 2023-01-22 at 6 31 57 PM" src="https://user-images.githubusercontent.com/122640173/213952443-9b31d384-8ea0-4802-9047-48742526a641.png">


Create Powershell Script <br/>
<img width="848" alt="Screen Shot 2023-01-21 at 5 14 09 PM" src="https://user-images.githubusercontent.com/122640173/213952535-e58d088c-8c2f-42a0-91ce-82f682e42b19.png">

Log showing Failed RDP <br/>
<img width="848" alt="Screen Shot 2023-01-21 at 5 14 09 PM" src="https://user-images.githubusercontent.com/122640173/213952535-e58d088c-8c2f-42a0-91ce-82f682e42b19.png">

Create a Custom Log <br/>
<img width="965" alt="Screen Shot 2023-01-22 at 7 03 24 PM" src="https://user-images.githubusercontent.com/122640173/213954557-6f41f540-7045-41a8-9366-e174ea0bf0aa.png">


Create custom fields  <br/>
<img width="965" alt="Screen Shot 2023-01-22 at 7 03 24 PM" src="https://user-images.githubusercontent.com/122640173/213954557-6f41f540-7045-41a8-9366-e174ea0bf0aa.png">


extract fields from raw custom log data  <br/>
<img width="935" alt="Screen Shot 2023-01-22 at 7 36 11 PM" src="https://user-images.githubusercontent.com/122640173/213957049-1990cda3-26a0-4738-b107-d9dd3c16187a.png">

 Setup map in sentinel with Latitude and Longitude (Create a New Workbook in Sentinel)  <br/>
<img width="834" alt="Screen Shot 2023-01-22 at 11 28 40 PM" src="https://user-images.githubusercontent.com/122640173/213981233-09dca6db-fc73-431f-aefc-06a6db82a1e9.png">

Wait a few hours and come back to microsfost sentinel to see Reults 
<img width="1242" alt="Screen Shot 2023-01-23 at 12 14 04 PM" src="https://user-images.githubusercontent.com/122640173/214129062-b81ad9ba-22a7-4ce7-ba4c-aeb9d3471bff.png">



<h2>Summary</h2>
I found this lab very interesting but also challenging at times , It allowed to me get some hands on experience with Microsoft azure and build on my past experiences with virtual machines .I Was very interested to see the source of the brute force attacks and look forward to exploring the possibilities of Microsoft sentinel  .
<br />


