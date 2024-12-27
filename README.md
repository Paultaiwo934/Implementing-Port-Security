<h1>Implementing Port Security</h1>

<h2>Description</h2>
In this project, I configured and verified port security on a switch. Port security restricts port’s ingress traffic by limiting the MAC addresses that are allowed to send traffic into the port.
<br />


<h2>Languages and Utilities Used</h2>

- <b>CLI</b> 


<h2>Environments Used </h2>

- <b>CISCO Packet Tracer</b> 

<h2>Program walk-through:</h2>

<p align="center">
Topology: <br/>
<img src="https://imgur.com/2eVn2GF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enabled port security on F0/1 and F0/2 and set the maximum devices that can access the ports to one:  <br/>
<img src="https://imgur.com/9k1HCTt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify port security is enabled and the MAC addresses of PC1 and PC2 were added to the running configuration: <br/>
<img src="https://imgur.com/RREJ8BA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A Rogue laptop was connected to port F0/2, this was flagged as a violation as only PC2 is allowed to connect to F0/2. Therefore, the rogue laptop could not ping PC1:  <br/>
<img src="https://imgur.com/t8yKBMS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
<img src="https://imgur.com/qX1P3SC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
