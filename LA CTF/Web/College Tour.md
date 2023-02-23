# College Tour 

<h1>Challenge Description</h1>

<img width="700" alt="college-tour" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/LA%20CTF/Web/LA%20Web%20Challenge.png">

<h2>Steps to get the flag: </h2>

1. According to the hint, six hidden clues are formatted as lactf{number_text}. I used the inspector tool and discovered clues from the index.html page. The first clues were an HTML comment, an HTML alt attribute, and the iframe source. 

<img width="700" alt="part-one-html" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/LA%20CTF/Web/First%20set%20of%20clues.png">

2. Next, I went to the CSS page and discovered that the secret font family was the fourth part of the flag: lactf{3_S3phI}.

<img width="700" alt="part-two-css" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/LA%20CTF/Web/index.png">

3. 

<img width="700" alt="part-three-js" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/LA%20CTF/Web/JS.png">

<h2>Flag</h2>
<p>lactf{j03_4nd_j0S3phIn3_bRU1n_sAY_hi}</p>
