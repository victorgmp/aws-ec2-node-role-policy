<!--
title: .'AWS EC2 instance running nodejs app'
description: 'AWS EC2 instance running nodejs app & a service using it to create GIFs'
framework: v3
platform: AWS
priority: 10
authorLink: 'https://github.com/victorgmp'
authorName: 'Víctor Moreno'
authorAvatar: 'https://avatars0.githubusercontent.com/u/16034468?v=4&s=140'
-->

# AWS EC2 instance running nodejs app with role, policy and elastic IP
```
git clone https://github.com/serverless/examples
```
## Usage

### Deployment
```
git clone https://github.com/serverless/examples
cd aws-ec2-node-role-policy
sls deploy
```

### Validation
```
LogIn in your AWS account and go to EC2 -> Intances and and validate that the EC2 instance was created and is running
```