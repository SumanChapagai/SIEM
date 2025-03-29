<h1>SIEM Lab in Azure</h1>


<h2>Description</h2>
Using Virtualization to create a SIEM lab to detect events, intrusions, and threats.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Sentinel</b> 

<h2>Environments Used </h2>

- <b>Azure</b>
- <b>Windows 10 pro VM</b>

<h2>Program walk-through:</h2>

<p align="center">
Setting up Azure: <br/>
<p>Create a VM in Azure, with preset configurations.</p>
<img src="https://i.imgur.com/BkGLT00.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring VM settings:  <br/>
<img src="https://i.imgur.com/bKUjvEh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TjRn8ij.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/KVaD1Dt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Microsoft Sentinel: <br/>
<img src="https://i.imgur.com/xJlXMl3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/3aEovsZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Checking VM status and settings:  <br/>
<img src="https://i.imgur.com/RUYWJSl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding Logger with Microsoft Sentinel:  <br/>
<img src="https://i.imgur.com/6YPmEPb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding SIEM to Sentinel:  <br/>
<img src="https://i.imgur.com/y1sXoQW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bTfXr3K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/KBSDLq9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data Collection Rule creation for SIEM:  <br/>
<img src="https://i.imgur.com/Hb7yPuR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating rule to log sign on events: <br/>
<img src="https://i.imgur.com/g2vrpmV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connecting to VM:  <br/>
<img src="https://i.imgur.com/ED8W9Wx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logged sign in:  <br/>
<img src="https://i.imgur.com/wTpcGJh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Finalization and connection test:  <br/>
<img src="https://i.imgur.com/ZcE0OjJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
