<h1> Angie's Write-up for Soda (Beginner) </h1>

<h2>Challenge description</h2>

<img width="1000" alt="reverse engineering challenge" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/Buckeye%20CTF/Reverse%20Engineering/Soda%20description.png?raw=true">

<h3>Steps to get the flag</h3>
For this challenge, I first downloaded the soda.jar file and decompiled it by using a free and online <a href="http://www.javadecompilers.com">Java decompiler</a>. Getting this flag took lots of trial and error because the objective was to purchase the most expensive soda, and we had to ensure it was within our budget. - I was only given a budget of $5.00 to purchase the soda from the vending machine. I used the commands to get the soda: purchase, wait, tap, reach, and grab. I had to reconnect to the server until the most expensive soda was under $5.00, and then I would purchase it immediately, but I received an error message that the soda was stuck. Next, I used the tap command to trick the program a few times so I would not reach for the soda.  From there, I decided to use the wait 10 seconds command so it wouldn't be that obvious that I could reach for the soda. Afterward, I used the reach command, and the most expensive soda would fall for the vending machine. I used the grab command to get the flag, which worked. 
