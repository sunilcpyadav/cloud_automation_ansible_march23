## Setting up your AWS Account

1. Create a new AWS Account (if you don't have already one). Creating an AWS account is free and AWS gives you 750 hours free compute (EC2) run-time for t2.micro instances. This would be sufficient for this class. You have to provide your credit card during the registration, but it won't be charged.

2. Log in to your new account to the AWS console and set up a free-tier billing alarm. You will get an email when you consumed more than 80% of the free-tier limits. This is just a safety measure, likely we don't use more than 20% of the free-tier resources during this class. (Billing / Billing Preferences / Receive Free Tier Usage Alerts)
  
3. Go to the Identity Access Management (IAM) and create a new user with admin rights. Ansible will create cloud resources through this user.

	- IAM / Users / Add Users
  - Click programmatic access
  - Click AWS Management Console Access
  - Set up a custom password
  - Next permissions
  - Create a new group called Admin
  - Attach AdministratorAccess to the group and click Create
  - Download the access key-pair generated for the user (access key ID and secret access key)
  
4. 

