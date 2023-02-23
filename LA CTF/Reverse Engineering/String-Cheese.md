# String-Cheese 

<h1>Challenge Description</h1>

<img width="700" alt="string-cheese-description" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/LA%20CTF/Reverse%20Engineering/String-Cheese-description.png">

<h2>Steps to get the flag: </h2>

After downloading the binary file, the first thing I did was look at the challenge description. The title of this challenge has the word "string" in it. I also noticed that in Linux, there is a command called strings. I used strings string_cheese and discovered that the cheese connoisseur's favorite flavor is blueberry. Finally, I connected to nc lac.tf 31131, answered the favorite cheese flavor question, and got the flag. 

<h2>Flag</h2>
<p>lactf{d0n7_m4k3_fun_0f_my_t4st3_1n_ch33s3}</p>
