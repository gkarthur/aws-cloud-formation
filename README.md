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
## Configure AWS Credentials

```
aws configure
AWS Access Key ID [None]: xxxxx
AWS Secret Access Key [None]: yyyyy
Default region name [None]: us-east-2
Default output format [None]:
```

## Create VPC and Subnet

To create 1 VPC and 1 Subnet

```
aws cloudformation create-stack --template-body file://vpc-create.yml --stack-name st001
```

To delete statck

```
aws cloudformation delete-stack --stack-name st001
```



