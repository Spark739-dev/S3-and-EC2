# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# NAME: VESHWANTH
# REG NO: 212224230300
# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3.

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard.

Step 3: Create Bucket Click the Create bucket button.

Step 4: Configure Bucket Settings

# • Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access.

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none).

Step 9: Advanced Settings (optional) Add tags, configure logging, etc.

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

# Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

# Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

# • Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances. Select your instance → Instance State → Terminate.

# OUTPUT:
# CREATING A NEW INSTANCES:
![WhatsApp Image 2025-09-21 at 22 20 54_7e90d833](https://github.com/user-attachments/assets/f514a0be-347b-4d2d-9842-5529054935a0)
# CREATING A BUCKET IN S3:
![WhatsApp Image 2025-09-21 at 22 29 51_2d78e5c8](https://github.com/user-attachments/assets/a87c106f-5ba5-4ac4-bab5-7c3b60a33824)
# CREATING NEW INSTANCES IN EC2:
![WhatsApp Image 2025-09-21 at 22 35 06_584a667a](https://github.com/user-attachments/assets/63aac0d8-b3cf-4c1e-a742-df6daa8352ab)

# OVERVIEW OF EC2 STORAGE INSTANCES:

![WhatsApp Image 2025-09-21 at 22 41 09_81469161](https://github.com/user-attachments/assets/e8daf8b3-025a-44f8-b4b6-7498a0a502d4)
# INSIDE NEW INSTANCES STORAGE EC2:
![WhatsApp Image 2025-09-21 at 22 40 13_fcfdb855](https://github.com/user-attachments/assets/058348e8-ba7d-4163-bfa7-601e4b7e7b9a)

# S3 OPERATIONS (DELETING,INSERTING)
<img width="1365" height="682" alt="image" src="https://github.com/user-attachments/assets/e9818627-da7d-4927-ad5c-402f90a6b55b" />
<img width="1067" height="587" alt="image" src="https://github.com/user-attachments/assets/33f5cb30-08b6-4738-8ae5-5f7eb41dfe4c" />
<img width="1357" height="614" alt="image" src="https://github.com/user-attachments/assets/34d635e7-73f1-43fc-bef7-d3af0c073d06" />

