Deploy a high-availability web app using CloudFormation

Load Balancer DNS URL: http://proje-webap-3qe3e6g09wnw-1618859489.us-east-1.elb.amazonaws.com/

C:\Users\HP\Desktop\BSES>aws cloudformation create-stack --stack-name Project2Mukul --template-body file://Solution.yml  --parameters file://Parameters.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1
{
    "StackId": "arn:aws:cloudformation:us-east-1:251181006302:stack/Project2Mukul/75b0cba0-30a2-11ee-8b8d-0e62783620b5"
}
