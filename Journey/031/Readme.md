# Day 31

90% through the A Cloud Guru course! Learned about Amazon SQS Delay Queues, CLI pagination, the AWS IAM Policy Simulator, and AWS Lambda concurrent execution limits.

Spent a little more time with Amazon Cognito and figured out how to [authenticate via the command line](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/cognito-idp/initiate-auth.html):

```
$ aws cognito-idp initiate-auth --client-id <the app client id> --auth-flow USER_PASSWORD_AUTH --auth-parameters USERNAME=<the username>,PASSWORD=<the password>
```

# Resources

- A Cloud Guru's [Certified Developer Associate](https://acloud.guru/learn/aws-certified-developer-associate) course
- [AWS CLI Reference - initiate-auth](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/cognito-idp/initiate-auth.html)

# Social proof

[The tweet](https://twitter.com/jennapederson/status/1294104153216737280?s=20)
