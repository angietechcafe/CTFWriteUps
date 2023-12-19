<h1> Angie's Write-up for Secret Seeker </h1>

<h2>Challenge description</h2>

<img width="700" alt="AWS EKS Cluster Challenge" src="https://github.com/angietechcafe/CTFWriteUps/assets/22628008/54eb002d-e0bf-4c60-be79-c13bb9a1b839">

<h3>Steps to get the flag</h3>
The first thing I did was view the permissions from the AWS EKS cluster. Then, I used the AWS Kubernetes help command. I.e., kubectl --help. 
Afterward, I typed kubectl edit secrets. I saw the flag, and it was in base64. I closed the file, used CyberChef to decode it, and got the flag.

<img width="700" alt="kubectl1" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/EKS%20Cluster%20Games/Kubectl%201.png?raw=true">

<img width="700" alt="kubectl1" src="https://github.com/angietechcafe/CTFWriteUps/blob/main/EKS%20Cluster%20Games/kube%20flag%20cyberchef.png?raw=true">

<h3>Flag</h3>
<p>wiz_eks_challenge{omg_over_privileged_secret_access}</p>
