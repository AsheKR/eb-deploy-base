# EB Deploy base

## Requirements

### brew

- awsebcli
- awscli

### ENV

- Production
  - AWS_SECRETS_MANAGER_ACCESS_KEY_ID
  - AWS_SECRETS_MANAGER_SECRET_ACCESS_KEY

- Dev
  - Credentials Profile (`lhy-secrets-manager`)

### AWS IAM

- User
  - AutoScalingFullAccess
  - ElasticLoadBalancingFullAccess
  - AWSElasticBeanstalkFullAccess
- Role (`aws-elasticbeanstalk-ec2-role`)
  - AmazonEC2ContainerRegistryReadOnly

