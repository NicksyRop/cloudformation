Create stack
aws cloudformation create-stack --stack-name MyNetwork --template-body file://vpc.yaml

Validate template
aws cloudformation validate-template --template-body file://vpc.yaml

Describe stack
aws cloudformation describe-stacks --stack-name MyNetwork

Update stack
aws cloudformation update-stack --stack-name MyNetwork --template-body file://testcfn.yml

aws commands
https://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html#cli-aws-cloudformation
