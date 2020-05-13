# AutoscaledService_Cloudformation
This is a cloudformation template to setup a AWS infrastructure for an autoscaled service
Instructions to use this cloudformation template
use your key and amiID (Amazon linux ami)
   keyName:
     Type: 'AWS::EC2::KeyPair::KeyName'
     Default: <use your keyname here>
   amiId:
     Type: String
     Default: <Amazon linux ami>

Commandline(AWS CLI) command to deploy this template : 
aws cloudformation create-stack --stack-name test --template-body file://Desktop\CF\test_cloudformation.yml

Or

Upload this template directly over the AWS Cloudformation console
