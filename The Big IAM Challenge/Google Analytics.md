<h1>Angie's Google Analytics (10 points)</h1>

<h2>Challenge Description</h2>
<p>We created our own analytics system specifically for this challenge. We think it's so good that we even used it on this page. What could go wrong?

Join our queue and get the secret flag.</p>

<img  width="700" alt="sqs-policy" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/SQS%20IAM%20Policy.png?raw=true">

<h3>Steps to get the flag</h3>
<p>The first thing I did was identify the AWS IAM policy. It states that I can send and receive SQS messages. The challenge description also showed that we ought to use a queue to receive the flag. I also noticed the ARN, created a queue URL and received a message.</p>
  
<img  width="700" alt="sqs-receive-message" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/SQS%20Receive%20Message.png?raw=true">

<p>Flag: {wiz:#######-#######-#####-##-###} </p>
