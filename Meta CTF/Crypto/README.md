<h1>Meta CTF 2021 </h1>

<h2>Angie's Write-up for Thnks fr th Pwds (100 points)</h2>

<h3>Challenge description:</h3> 

<p>On a red team engagement, you discover a text file on an administrator’s desktop with all of their passwords - you now have the keys to the kingdom!

During the engagement debrief, you explain what you found and how you were able to access so many systems. The administrator says that's impossible, because they encrypted all of the passwords in the file.

Here’s an example of one of their “encrypted” passwords: TWV0YUNURntlbmNvZGluZ19pc19OMFRfdGhlX3NhbWVfYXNfZW5jcnlwdGlvbiEhfQ==

See if you’re able to recover the Administrator's password.</p>

<h2>Steps to get the flag</h2>
<p> 1. The two equal signs at the end of this encoded string represents Base64.</p>
<p> 2. In order to decrpyt this password, we can use a Base64 decrpyt tool such as CyberChef. 
I used the From base64 recipe to solve this challenge.</p>

<img width="1129" alt="base64 challenge" src="https://user-images.githubusercontent.com/22628008/160703617-63151796-093d-4655-882c-99211f5dbba5.png">

<h2>Flag</h2>
<p>MetaCTF{encoding_is_N0T_the_same_as_encryption!!}</p>
