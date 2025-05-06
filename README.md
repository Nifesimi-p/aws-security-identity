# aws-security-identity
# AWS Security & Identity Assignment

## 1. Create IAM User with Restricted Permissions
- User: `restricted-user`
- Permission: AmazonS3ReadOnlyAccess
- Tested with access to create S3 bucket(denied)
- ![S3 Access Screenshot](./IMAGES/Permissiondenied.png)
  
## 2. Setup MFA
- Used Passcode
- Creating MFA
- ![MFA Screenshot](./IMAGES/MFA1.png)
- Created MFA
- ![MFA Screenshot](./IMAGES/MFA2.png)
- Successfully tested MFA login
- ![MFA Screenshot](./IMAGES/MFA3.png)

## 3. Custom Policy and Role
- Policy: `EC2ReadOnlyCustomPolicy`
- Role: `ec2-readonly-role`
  
### Screenshots
- Allows EC2 describe actions only
- ![Policy Screenshot](./IMAGES/Policycreated.png)
- Creating Role
- ![Role Screenshot](./IMAGES/Role1.png)
- Attached a custom policy to an IAM role
- ![Role Screenshot](./IMAGES/Role2.png)

