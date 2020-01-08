# buildwithAWS # DevOps

## Quickly Configuring the AWS CLI

```
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-east-1
Default output format [None]: json
```

## Creating a Key Pair

Create "demo-us-east-1" key pair following [Creating a Key Pair](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-key-pairs.html#having-ec2-create-your-key-pair)

## Run the ansible-playbook

```
ansible-playbook -vvvv ./playbooks/deploy-demo-stack.yml
```

## The pipeline looks as follows:

![CodePipeline](images/pipeline.png)

## LAMP Stack Deployment with PHP and RDS:

![LAMP Stack with PHP and RDS](images/php.png)

