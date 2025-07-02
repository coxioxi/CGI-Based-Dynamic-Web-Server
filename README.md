<h1>CGI Based Dynamic Web Server</h1>

<h2>Description</h2>
This project demonstrates the core principles of Common Gateway Interface (CGI) programming using the C language. It simulates how dynamic web content is generated and served through HTTP requests by executing C programs that output HTML.

The server accepts both GET and POST requests, sets up the appropriate environment variables, and executes CGI programs based on the requested URI. These CGI programs then process data and return dynamically generated HTML responses.
<br />


<h2>Languages and Utilities Used</h2>

- <b>C</b> 
- <b>Shell (Bash)</b>
- <b>GCC</b>
- <b>MakeFile Syntax</b>

<h2>Environments Used </h2>

- <b>Linux (Ubuntu)</b> 

<h2>Program walk-through:</h2>

<p align="center">
Input File "exp.txt": <br/>
<img src="https://imgur.com/cKuOq98.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
HTML Output:  <br/>
<img src="https://imgur.com/qmtAuXp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Record 2 from "data.txt" Input: <br/>
<img src="https://imgur.com/rd4BPEi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
HTML Output:  <br/>
<img src="https://imgur.com/9fG60bE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
HTML output from query "db=exp.txt&record=2":  <br/>
<img src="https://imgur.com/lLoQEHE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
