# VICON-JS-Extension
Chrome malicious extension that steals all the Keystrokes on the keyboard, with Trojanized Chrome loaded with Rubber Ducky payload 
Extension maliciosa de Chrome que roba todos los inputs del teclado. Troyando el chrome con un Payload de Rubber Ducky


# Content
Main files (manifest and content) should be in the same folder, and load the folder with the technique described on the slideshow.
Please, change the content.js to the server that you need.
Content is ofuscated. Please, if you need the original code, refer to "demo.js"


# Usage
Upload server.php to your own server, and set the server variable in content.js 
Load the extension


# Todo
Bash script, Ps1 script and VBA functional script that allows the same behaviour than Rubber Ducky
Better method to not simply have a full list of arrays (maybe regex on the server to classify information).
Metasploit Post/explotation module
Do a web-ui, not a data.txt, for managing results.
Improve the Keylogger with other cappabilities as screen capture, or not sendind periodically the keystrokes
Do a binder with an original extension trying to bypass store protections
Think other creative methods to load the ext.
Add a custom header to prevent trolling :D
Implement a fully c2c shell with JSSHELL
Other SE attacks like popping up lastpass/keypass nags

# Disclaimer
This repo is only for investigation purpouses, Pls, dont blame me if something is not working for u.
Dont use ir for malicious things.


# Thanks
Original Keylogger from
https://github.com/JohnHoder
![image](https://user-images.githubusercontent.com/52542268/162731480-db0cc83e-d6f5-48e7-a44a-8b8b8a662a95.png)
