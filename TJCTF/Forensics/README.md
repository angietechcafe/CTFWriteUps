<h2>Angie's Write-up for fake-geoguesser (227 points)</h2>

<h3>Challenge description</h3>

<p>We don't do guess challs here at TJCTF, so that means no Geoguessr 😔 Since I took this photo myself, 
though, you can find out precisely where it was taken, and some Bonus Content™, from my Camera Model Name 
to the Circle Of Confusion. Maybe you'll find a flag there?</p>

<h2>Steps to get the flag</h2>

<p>First, I downloaded the lake image from the TJCTF challenge site. Afterwards, I used an online forensics tool called Forensically Beta so I can analyze the image. On the fifth line, I saw bits of the flag starting with "tfjcf" and knew that it was the first section of the flage. Finally, I scrolled down ever further on Forensically Beta and saw the last section of the hidden message. When I put the pieces together, the flag was tjctf{thats_a_lot_of_metadata}</p>

<img width="602" alt="forensicallyOne" src="https://github.com/angieintech/CTFWriteUps/blob/main/TJCTF/Forensics/forensicallyOne.png?raw=true">
<img width="602" alt="forensicallyTwo" src="https://github.com/angieintech/CTFWriteUps/blob/main/TJCTF/Forensics/ForensicallyTwo.png?raw=true">

<h2>Flag</h2>
<p>tjctf{thats_a_lot_of_metadata}</p>
