EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team
NAME: MOPURI SARADEEPIKA
REG. NO: 212224040201
Aim
To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

Algorithm
Sign in to the AWS Management Console.
Navigate to the IAM service.
Create IAM groups with defined policies (e.g., Admin, Developer).
Create IAM users and assign them to appropriate groups.
Create IAM roles if cross-account or service-based access is needed.
Attach permissions using managed or custom policies.
Enable MFA (Multi-Factor Authentication) for users.
Monitor access using IAM Access Analyzer and CloudTrail.

Procedure
1. Access IAM
Go to AWS Console → Services → IAM.
2. Create IAM Groups
Click Groups → Create New Group.
Name the group (e.g., Admins, Developers).
Attach predefined or custom policies (e.g., AmazonEC2FullAccess).
3. Create IAM Users
Click Users → Add Users.
Enter usernames and choose Programmatic access and/or AWS Management Console access.
Assign users to the appropriate group.
4. Create IAM Roles (if needed)
Go to Roles → Create Role.
Select use case (AWS service, another AWS account).
Attach necessary permissions.
5. Apply Policies
Use AWS managed policies or create custom JSON-based policies.
Assign them to users, groups, or roles.
6. Enable MFA
For each user, go to Security credentials.
Click Manage MFA → Choose Virtual MFA device (e.g., Google Authenticator).
7. Monitor IAM Usage
Use IAM Access Analyzer to detect unused permissions.
Use CloudTrail for auditing user activity.
Outcome
1.IAM Group Creation
<img width="1152" height="465" alt="image" src="https://github.com/user-attachments/assets/f89abb72-d526-458c-a54e-8f98b013263b" />

2.Attach an IAM Policy to the group
<img width="1143" height="450" alt="image" src="https://github.com/user-attachments/assets/0c2f5077-bd7a-4f4c-86a9-49b8e55699a8" />

3.Create an IAM User
<img width="1152" height="485" alt="image" src="https://github.com/user-attachments/assets/87af37a4-f59b-43ea-9ccc-e5cf82bb789e" />

4.Add The user to the IAM Group
<img width="1152" height="448" alt="image" src="https://github.com/user-attachments/assets/bb6bdb02-d2c8-4479-9b74-c1c75f6dac91" />

5.Verify user Permissions
<img width="1147" height="482" alt="image" src="https://github.com/user-attachments/assets/0ae6ad18-c6b0-4b35-87b5-50a42a2dce90" />

6.Verify Least-Privilege Access
<img width="1143" height="437" alt="image" src="https://github.com/user-attachments/assets/9340657e-6e4b-4152-898e-6bc1bdd8ff81" />

<img width="1148" height="486" alt="image" src="https://github.com/user-attachments/assets/7aa20313-2fc0-48ef-b0a6-9fa80cf2fa6a" />

Result
Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
