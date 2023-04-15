<h1> Angie's Write-up for Soda (Beginner) </h1>

<h2>Challenge description</h2>

<img width="700" alt="reverse engineering challenge" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/BuckeyeCTF/Soda%20description.png?raw=true">

<h3>Steps to get the flag</h3>
<p>For this challenge, I first downloaded the soda.jar file and decompiled it by using a free and online <a href="http://www.javadecompilers.com">Java decompiler</a>. By looking at the drink class property, it was interesting to note that the stuck variable was 3. This was a big hint for capturing this flag. Getting this flag took lots of trial and error because the objective was to purchase the most expensive soda, and we had to ensure it was within our budget. - I was only given a budget of $5.00 to purchase the soda from the vending machine. I used the commands to get the soda: purchase, wait, tap, reach, and grab. I had to reconnect to the server until the most expensive soda was under $5.00, and then I would purchase it immediately, 
  but I received an error message that the soda was stuck. Next, I used the tap command to trick the program a few times so I would not reach for the soda.  From there, I decided to use the wait 11 seconds command so it wouldn't be that obvious that I could reach for the soda. 
  Afterward, I used the reach command, and the most expensive soda would fall for the vending machine. 
  I used the grab command to get the flag, which worked. <p>
  
<img width="700" alt="purchase soda" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/BuckeyeCTF/Purchase.png?raw=true">
<img width="700" alt="tap and wait 11" src="#">
<img width="700" alt="reach and grab soda flag" src="#">
