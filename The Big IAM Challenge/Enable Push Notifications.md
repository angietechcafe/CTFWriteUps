<h1>Angie's Enable Push Notification Writeup (10 points)</h1>

<h2>Challenge Description</h2>
<img  width="700" alt="sns-policy" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/Enable%20Push%20Notifications%20Description.png?raw=true">

<img  width="700" alt="sns-policy" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/AWS%20SNS%20IAM%20POLICY.png?raw=true">

<h3>Steps to get the flag</h3>
<p>The first thing I did was identify the AWS IAM policy. It states that I can enable a push notification with the endpoint. I looked at the documentation regarding subscribing to an SNS notification with the following command: "aws sns subscribe \
    --topic-arn arn:aws:sns:us-west-2:123456789012:my-topic \
    --protocol email \
    --notification-endpoint 'my-email@example.com' ". I changed the notification endpoint with the one provided by Wiz as well as my topic-arn and pressed enter. Afterward, I received a pending confirmation - however, I did not set up an email to receive this notification, so I needed a webhook to get the flag. I realized I needed a webhook after receiving an error message from AWS CLI. I attempted to create a Python Flask webhook to subscribe to the SNS notification but received an error.   </p>

<img  width="700" alt="sns pending confirmation" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/SNS%20Subsription%20Pending.png?raw=true">

<img  width="700" alt="sns-webhook-error" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/The%20Big%20IAM%20Challenge/SNS%20error%20message.png?raw=true">

<img  width="700" alt="sns-receive-message" src="#">

<p>Flag: {} </p>
