<h1>Angie's Enable Push Notification Writeup (10 points)</h1>

<h2>Challenge Description</h2>
<p> </p>

<img  width="700" alt="sns-policy" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/AWS%20SNS%20IAM%20POLICY.png?raw=true">

<h3>Steps to get the flag</h3>
<p>The first thing I did was identify the AWS IAM policy. It states that I can enable a push notification with the endpoint. I looked at the documentation regarding subscribing to a sns notification with the following command "aws sns subscribe \
    --topic-arn arn:aws:sns:us-west-2:123456789012:my-topic \
    --protocol email \
    --notification-endpoint my-email@example.com". I changed the notification endpoint with the one provided by Wiz as well as my topic-arn and pressed enter. However I did not setup an email to receive this notifcation so I needed a webhook in order to get the flag. 
<img  width="700" alt="sqs-receive-message" src="#">

<p>Flag: {} </p>
