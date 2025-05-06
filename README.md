# aws-security-identity
# AWS Security & Identity Assignment

## 1. Create IAM User with Restricted Permissions
- User: `restricted-user`
- Permission: AmazonS3ReadOnlyAccess
- Tested with access to S3 (success) and EC2 (denied)
- ![S3 Access Screenshot](screenshots/s3-access.png)
- ![EC2 Access Denied Screenshot](screenshots/ec2-denied.png)

## 2. Setup MFA
- Used Google Authenticator
- Successfully tested MFA login
- ![MFA Screenshot](screenshots/mfa-success.png)

## 3. Custom Policy and Role
- Policy: `EC2ReadOnlyCustomPolicy`
- Role: `ec2-readonly-role`
- Allows EC2 describe actions only
- ![Policy Screenshot](screenshots/policy-created.png)
- ![Role Screenshot](screenshots/role-attached.png)

## 4. Screenshots
- Place all screenshots inside `/screenshots` folder in the repo
