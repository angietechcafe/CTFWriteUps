<h1>Angie's AWS Buckets of Fun Writeup (10 points)</h1>

<h2>Challenge Description</h2>
<p>We all know that public buckets are risky. But can you find the flag?</p>

<img  width="700" alt="bucket-policy" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/AWS%20Bucket%20Policy.png?raw=true">

<h3>Steps to get the flag</h3>
<p>The first thing I did was identify the AWS IAM policy. In this case, I can access a list of objects. The first hint was the prefix */files. I looked at the AWS documentation and used this AWS command "aws s3api list-objects --bucket thebigiamchallenge-storage-9979f4b --prefix files". There is a flag text file here. Afterward, I downloaded an object from S3 using the following command, "aws s3api get-object --bucket thebigiamchallenge-storage-9979f4b --key files/flag1.txt flag1.txt" and lastly used cat flag1.txt to view the flag. I will not show the exact answer to this challenge because folks can still access it. This was an overall fun challenge about IAM in AWS. </p>

<img  width="700" alt="list-objects" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/list%20object.png?raw=true">

<p>Flag: {wiz:#######-#######-#####-##-###} </p>
