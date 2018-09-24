# aws-cloud-formation

Here you can find the basics aws cloud formation templates

## Configuration
Get your code access allow to execute AWS CLI.
Run the configure command:

```
aws configure
```

Then get code source

```
mkdir git
cd git
git clone https://github.com/gkarthur/aws-cloud-formation.git
cd aws-cloud-formation
```

## Create VPC and Subnet

To create 1 VPC and 1 Subnet

```
aws cloudformation create-stack --template-body file://vpc-create.yml --stack-name st001
```



