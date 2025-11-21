## Ex.2 Cloud Storage Creation (S3) and Launching an EC2 Instance in AWS
## NAME : VARSHA K
## REG NO : 212223220122
## Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

## Procedure
## a) Steps to Create a First S3 Bucket
1.Sign in to AWS Management Console

Go to: https://console.aws.amazon.com/s3
2. Open the S3 Service

Search for S3 in the search bar and open it.
3. Create Bucket

Click the Create bucket button.
4.Configure Bucket Settings

Bucket name: Choose a globally unique name.
AWS Region: Select the region where you want to store your data.
5.Object Ownership

Choose:
ACLs disabled (recommended) — Bucket owner has full control.
ACLs enabled — Control access via access control lists.
6.Block Public Access Settings

By default, public access is blocked. Leave it as-is unless you need public access.
7.Bucket Versioning (Optional)

Choose whether to enable versioning for objects in the bucket.
8.Encryption (Optional)

Select encryption options: SSE-S3, SSE-KMS, or none.
9.Advanced Settings (Optional)

Add tags, configure logging, etc.
10.Create the Bucket

Click Create bucket at the bottom of the page.
## b) Steps to Launch an EC2 Instance
Go to the EC2 Dashboard in AWS Console.
Click on Launch Instance.
Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
Select an Instance Type (e.g., t2.micro for Free Tier).
Create or Choose a Key Pair for SSH access.
Configure Network Settings (use default VPC/subnet).
Configure Storage (default root volume is fine).
Review and Launch
Review settings and click Launch Instance.
Wait for the instance to enter the running state.
## c) Connect to Your EC2 Instance
Linux Users: Use SSH command with your .pem key.
Windows Users: Use RDP with decrypted admin password.
## d) Steps to Clean Up (Terminate the Instance)
Go to EC2 Instances.
Select your instance → Instance State → Terminate.
## Snapshots
Snap Shot 1: Simple Storage Service (S3)
<img width="745" height="396" alt="image" src="https://github.com/user-attachments/assets/6c1064d7-9cf8-4cde-91b7-11496d6aa808" />

Snap Shot 2: EC2 (Elastic Compute Cloud) – Instance
<img width="754" height="403" alt="image" src="https://github.com/user-attachments/assets/933a8806-0d2e-4d46-9b7e-e2993929c1c7" />
Result
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.
