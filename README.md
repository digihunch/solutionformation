## Table of contents
* [General info](#general-info)
* [Useful Command](#usefule-command)
* [Setup](#setup)

## General info
This is cloudformation template
	
## Useful Commands
Cloudformation template

aws cloudformation validate-template --template-body file://SolutionStack.yml

aws cloudformation create-stack --stack-name mytest --template-body file://SolutionStack.yaml --capabilities CAPABILITY_NAMED_IAM

aws cloudformation delete-stack --stack-name mytest

aws cloudformation describe-stack-events --stack-name mytest

aws cloudformation list-stacks --stack-status-filter CREATE_COMPLETE

## Setup
Run AWS cli command
Note: user executing the aws cli command needs to have the following permissions:

1. CloudFormation full privilege

2. Privilege to allow cloudformation tempalte to do what it needs to do (Administrator Access should be given if there are too many low privilege accesses are needed)

```
