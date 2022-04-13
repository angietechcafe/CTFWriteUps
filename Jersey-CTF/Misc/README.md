<h2>Angie's Write-up for root-me (400 points)</h2>

<h3>Challenge description</h3>

<p>SSH into the challenge host, 0.cloud.chals.io on port 19777.
   
   Username: ubuntu 
   Password: jctf2022!
   
   Find the flag.</p>


<h2>Steps to get the flag</h2>
<p>First I ssh into the Ubuntu box and I realized that I could not use vim, sudo or install anything on this box. The challenge says to find the flag so I took it literally and used the find linux command. I ended up using the perm option to gain permission as well as finding a specific file type. I also used the 2>/dev/null to view errors and look for stickybit for the user with this parameter: u=s. I could not read it by simply using a cat command. Afterwards, I googled Linux date, and discovered gtfob date website link. Then I clicked on the link and followed the format: LFILE=file_to_read. I typed date -f $LFILE and got weird date messages. That is a clue of finding the flag because Linux dates are not usually presented in this format. It also said that they're invalid dates. Now that I know how it works, I will try the LFILE with /root/flag.txt and voila a flag. Found the flag by luck and believed it would be a text file since the challenge mentioned that there was a flag file located in this box. </p>

<img width="602" alt="sshlogin" src="https://github.com/angieintech/CTFWriteUps/blob/main/Jersey-CTF/Misc/SSH%20Login.png?raw=true">

<img width="602" alt="findcommand" src="https://github.com/angieintech/CTFWriteUps/blob/main/Jersey-CTF/Misc/find%20command%20linux.png?raw=true">

<img width="602" alt="rootme" src="https://github.com/angieintech/CTFWriteUps/blob/main/Jersey-CTF/Misc/Lfile_date.png?raw=true">

<img width="602" alt="rootflag" src="https://github.com/angieintech/CTFWriteUps/blob/main/Jersey-CTF/Misc/root_flag.png?raw=true">


<h2>Flag</h2>
<p>jctf{4cc355_6r4n73d}</p>
