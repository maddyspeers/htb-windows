<h1>HTB - Tactics (Windows)</h1>

<h2>Description</h2>
<b>Tactics</b> is an easy-level Windows machine on Hack The Box that focuses on authenticated SMB access. The challenge involves using smbclient to access administrative shares and retrieve the flag. The machine is a great introduction to SMB enumeration, Windows file structure navigation, and privilege validation.

<h2>About</h2>

- **🎚️ Difficulty:** Easy

- **💻 Category:** Windows/SMB

- **🔎 Tools Used:** nmap, smbclient

<h2>Machine Walk-Through:</h2>

<p align="center">
Checking to see if SSH is open: <br/>
<img src="https://i.imgur.com/8Q30dlI.png" height="50%" width="50%" alt="Machine"/>
<br />
<br />
<p align="center">
Nmap scan to see which ports are open: <br/>
<img src="https://i.imgur.com/BCB2OZE.png" height="50%" width="50%" alt="Machine"/>
<br />
<br />
<p align="center">
SMB port is open: <br/>
<img src="https://i.imgur.com/jfr8Id7.png" height="50%" width="50%" alt="Machine"/>
<br />
<br />
<p align="center">
Copy flag to Linux machine: <br/>
<img src="https://i.imgur.com/eRpXX5W.png" height="50%" width="50%" alt="Machine"/>
<br />
<br />
<p align="center">
Read flag on Linux machine: <br/>
<img src="https://i.imgur.com/gKmlVPc.png" height="50%" width="50%" alt="Machine"/>
<br />
<br />
