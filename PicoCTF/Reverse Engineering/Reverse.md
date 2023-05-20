<h1> Angie's Write-up for Reverse (100 Points) </h1>

<h2>Challenge description</h2>

<img width="700" alt="RE challenge" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/PicoCTF/Reverse%20Engineering/Reverse.png?raw=true">

<h3>Steps to get the flag</h3>

<p>For this challenge, I used the wget command to download the ELF 64 binary file and decompile it with a reverse engineering tool, Ghidra. Next, I searched for the flag in the Classes folder but noticed that it only displayed a few sections of the flag. After my second attempt, I discovered the entire flag by checking the Functions folder with the _fini file.</p>

<img width="700" alt="reverse_one" src="#">
<img width="700" alt="reverse_one" src="#">
<img width="700" alt="reverse_one" src="#">
