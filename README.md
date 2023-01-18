<h1>Configuring IPv6 Addressing</h1>

<h2>Description</h2>
Project consists of configuring a router to connect tow LANs using IPv6 addressing. The connections are then verified using ping.
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>Cisco Packet Tracer</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Configure IPv6 Addressing:</h2>
Network Topology: <br/>
<img src="https://imagizer.imageshack.com/img924/9593/6C3QZ6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The router 1 CLI is accessed to enter global configuration mode and enable IPv6 routing: <br/>
<img src="https://imagizer.imageshack.com/img923/6439/Waxwpe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The router 2 CLI is accessed and the process is repeated. Both interfaces are enabled: <br/>
<img src="https://imagizer.imageshack.com/img923/1708/jg9E9n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The IPv6 interface brief is displayed to verify the configuration: <br/>
<img src="https://imagizer.imageshack.com/img924/4066/jaw8CR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The IPv6 address and Default Gateway is statically configured through User's 1-4 desktop: <br/>
<img src="https://imagizer.imageshack.com/img922/9096/UlWIWP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The ping command is used to verify connectivity to the router as well as the neighboring PC: <br/>
<img src="https://imagizer.imageshack.com/img923/498/ZgoxMe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
