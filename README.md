# bragsheet.html
Naval bragsheet app in JS/CSS/HTML

This is a working concept for an application that should aid the management of naval bragsheets.
The export format is a text file-- for now.
With feedback, the export format can be adjusted to more accurately reflect the needs of naval personnel.

<H3>Usage</H3>

<ul>
<li>1. Get and save file to known directory. </li>
<li>2. Open file with browser. </li>
</ul>

<H3>Install with Curl && Run for Windows, MacOS, and Linux with firefox</H3>

```console
curl https://raw.githubusercontent.com/lvcca/bragsheet.html/main/bragsheet.html -o bragsheet.html && bragsheet.html || open bragsheet.html || firefox bragsheet.html
```

![image](https://user-images.githubusercontent.com/49540886/131514510-aa32bd52-dbe3-43ab-ac6a-e55bb72f74f6.png)

![image](https://user-images.githubusercontent.com/49540886/131514822-6915e932-1c0e-43d9-a3fa-d552ea4c5ac0.png)

![image](https://user-images.githubusercontent.com/49540886/131514873-f2a646c7-f6df-4820-9e3b-0e942a8b79ea.png)


<H3>Files</H3>
<ul>
<li>Record.txt : JSON file with persistent data. <- <b>Upload this file</b></li>
<li>Bragsheet.txt : Formatted txt file with stored data.</li>
</ul>

![image](https://user-images.githubusercontent.com/49540886/131514950-b90db826-227c-42b6-8961-dcaf922e6f3c.png)
![image](https://user-images.githubusercontent.com/49540886/131514998-d7477d7c-09d7-4113-a82a-03c7b6e62e24.png)

<H3>TO DOs</H3>
<ul>
<li>Expand export to word document</li>
<li>Drag and drop import file</li>
<li>Remove import button and include onload import button function when file loaded</li>
<li>Implement smart sort by table position and clicked element</li>
</ul>
