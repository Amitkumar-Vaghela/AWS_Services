## 📷 IAM User Creation Screenshot

![AWS IAM User Created](https://github.com/Amitkumar-Vaghela/AWS_Services/blob/main/Screenshot%202025-12-28%20150938.png)

📘 AWS IAM (Identity and Access Management)
📌 What is AWS IAM?

AWS Identity and Access Management (IAM) is a service that helps you securely control access to AWS services and resources.
Using IAM, you can create users, groups, roles, and assign permissions.

🎯 Purpose of This Project

To understand AWS IAM basics

To create an IAM user

To provide console access with permissions

To follow best security practices

🧰 Services Used

AWS IAM

AWS Management Console

🪜 Step-by-Step Implementation
Step 1: Login to AWS Console

Go to: https://aws.amazon.com/console/

Login using Root account credentials

Step 2: Open IAM Service

Search IAM in the AWS search bar

Click on IAM → Users

Step 3: Create IAM User

Click Create user

Enter User name (example: Amit)

Enable AWS Management Console access

Choose Custom password or auto-generated password

(Optional but recommended) ✔ Force password reset

Step 4: Set Permissions

Choose one of the following:

✔ Add user to group (Recommended)

Attach policy (example):

AdministratorAccess (for learning)

ReadOnlyAccess (for safety)

Step 5: Review and Create

Review user details

Click Create user

✅ User created successfully

Step 6: Retrieve Console Login Details

After user creation:

Console Sign-in URL

Username

Console Password

⚠️ Important:
This is the only time you can view/download the password.

Step 7: Login as IAM User

Open the console sign-in URL

Enter username & password

Reset password if prompted

🔐 Security Best Practices

❌ Do not use Root account for daily work

✅ Use IAM users with least privilege

✅ Enable MFA (Multi-Factor Authentication)

✅ Use Groups instead of individual permissions

📂 Example IAM Use Cases

Developer access to EC2 & S3

Read-only access for monitoring

CI/CD pipeline permissions

Team-based access management

📷 Screenshot

IAM User creation & password retrieval page
(Screenshot attached in repo)

📘 What I Learned

How IAM controls AWS security

Difference between Root user and IAM user

Importance of permission policies

Secure AWS account management

🚀 Future Improvements

Create IAM Groups

Attach custom JSON policies

Enable MFA for IAM users

Create IAM Roles for EC2
