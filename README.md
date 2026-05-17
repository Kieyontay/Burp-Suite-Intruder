<h1>Burp Suite: Intruder </h1>


<h2>Description</h2>
This lab is an introduction to the basics of Burp Suite Intruder. Burp Suite Intruder is a tool that allows for repetitive testing with variations in input values. Burp Suite Intruder serves various purposes such as brute-forcing login forms by allowing users to substitute username and password fields with values from a wordlist.
<br />


<h2>Tools Used</h2>

- <b>Burp Suite Intruder</b>

<h2>Burp Suite Intruder Walkthrough:</h2>

<p align="center">
Navigate to the page you want to log into: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Try%20to%20Log%20In.png?raw=true" height="80%" width="80%" alt="Login page"/>
<br />
<br />
Send the request to Intruder:  <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Send%20POST:login%20to%20Intruder.png?raw=true"/><br />
<br />
<br />
Set payload position: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Set%20payload%20position.png?raw=true"/>
<br />
<br />
Paste payload: <br />
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Paste%20payload%20.png?raw=true" height="80%" width="80%" alt="Edit header"/> <br />
<br />
Start Sniper attack: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Start%20attack.png?raw=true"/> <br />
<br />
<br />
Study the response: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Study%20the%20response.png?raw=true" height="80%" width="80%" alt="Repeater Render Results"/> <br />
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Incorrect%20password.png?raw=true" height="80%" width="80%" alt="Request history"/> <br />
<br />
<br />
Repeat steps for password: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Password%20payload.png?raw=true" height="80%" width="80%" alt="Repeater unexpected results"/> <br />
<br />
<br />
Study the response: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Successful%20Brute%20Force%20.png?raw=true" height="80%" width="80%" alt="Repeater unexpected results"/> <br />
<br />
<br />
Use the login credentials from the attack to login: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Intruder/blob/main/Success.png?raw=true" height="80%" width="80%" alt="Repeater unexpected results"/> <br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
