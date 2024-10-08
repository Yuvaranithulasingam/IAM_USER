# IAM_USER

## AIM:
To create an IAM user in AWS, assign the user to a group, and provide programmatic access to the user for interacting with AWS services via AWS CLI or SDK.

## APPARATUS REQUIRED:
AWS Account</BR>
AWS Management Console</BR>
IAM Permissions</BR>

## THEORY:
AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create users, groups, and assign roles or permissions. Programmatic access allows the user to interact with AWS services via APIs, SDKs, or AWS CLI, instead of the Management Console.

### The key components of this experiment are:

IAM User: A user identity that can have long-term access credentials like access keys.</br>
IAM Group: A collection of users with common permissions.</br>
Programmatic Access: Grants the user an Access Key ID and Secret Access Key for use in AWS CLI/SDK/API.</br>
IAM Policies: Define permissions to allow or deny specific actions.</br>

## PROCEDURE:

Step 1: Log in to the AWS Management Console</BR>
Open the AWS Console and log in with an account that has permission to create IAM users and groups.</BR>

Step 2: Navigate to IAM Dashboard</BR>
From the AWS Management Console, search for IAM in the search bar and select the IAM service.</BR>

Step 3: Create a New User</BR>
On the left panel, click on Users, then select Add User.</BR>
Enter a username for the new IAM user.</BR>
Select the access type Programmatic Access (to generate an Access Key ID and Secret Access Key).</BR>

Step 4: Create a User Group</BR>
If a group for the user doesn't already exist, go to Groups on the left menu and create a new group.</BR>
Assign relevant permissions by attaching policies (e.g., AdministratorAccess, AmazonS3ReadOnlyAccess) to the group.</BR>
Add the user to the group by selecting the newly created group or any existing one.</BR>

Step 5: Attach Permissions </BR>
Choose appropriate policies based on the user's role. </BR>
For example:
AdministratorAccess for full access to all AWS services.</BR>
AmazonS3ReadOnlyAccess for read-only access to S3.</BR>

Step 6: Review and Create</BR>
Review the user's settings and click on Create User.</BR>
After creation, the access credentials (Access Key ID and Secret Access Key) will be displayed. Download them securely, as they will not be displayed again.</BR>

## OUTPUT:

![WhatsApp Image 2024-08-24 at 17 17 44_ec15c95a](https://github.com/user-attachments/assets/0cd216a1-d103-44da-b203-4917a388248b)

![WhatsApp Image 2024-08-24 at 17 17 44_2b88e3e5](https://github.com/user-attachments/assets/52dc9244-156f-4c84-bb98-3dcd5d3e14a1)

![WhatsApp Image 2024-08-24 at 17 17 15_de866db1](https://github.com/user-attachments/assets/032c34db-3a6f-4123-8600-96a8b8703481)

## RESULT:
You have successfully created an IAM user with programmatic access.The user is part of a group with assigned permissions.Programmatic access to AWS services is enabled using AWS CLI or SDK with the provided credentials.
