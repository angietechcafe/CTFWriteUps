<h1>Angie's Google Analytics (10 points)</h1>

<h2>Challenge Description</h2>
<p>We created our own analytics system specifically for this challenge. We think it's so good that we even used it on this page. What could go wrong?

Join our queue and get the secret flag.</p>

<img  width="700" alt="sqs-policy" src="#">

<h3>Steps to get the flag</h3>
<p>The first thing I did was identify the AWS IAM policy. It states that I can send and receive SQS messages. I also noticed the ARN, created a queue URL and received a message.
<img  width="700" alt="sqs-receive-message" src="#"
<p>Flag: {wiz:#######-#######-#####-##-###} </p>
