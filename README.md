# aws-saa-c02-labs

## Labs 01
1. Force MFA on AWS Console and CLI
- Create a user test and try to create different instances.
2. Limit ==create instance type== on each user
- Assgin user test to this group and check the results
3. Limit create instance location only in specify regions each user
- Assgin user test to this group and check the results

- [ ] is this OK ?

- [ ] Write the press release

## Labs 02
1. Create a simple website with index.html/error.html and uploadFile.html
2. User authenticate by Cognito Credential by AWS
- Create user infor on AWS Cognito credentials
- If user authen successfully so redirect to uploadFile.html
- Else display error.html page and display relogin button.
3. Add event on S3 bucket when a user upload new file and notication to Lambda
4. Lambda trigger notification and insert file information in a DynamoDB
5. User can list all file that uploaded on listUploadFile.html