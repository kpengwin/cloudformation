
### Example cloudformation create command
aws cloudformation create-stack --template-body file://simple-t2.micro.json --stack-name test-stack

### Example cloudformation delete command
aws cloudformation delete-stack --stack-name test-stack --output text
