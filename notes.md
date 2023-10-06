create aws account
add user and role

install aws cli in your system //follow aws docs
aws --version --check version

aws cloudformation - infra as code
CDK code ---synth---> CF template ---deploy---> AWS CF
create a stack or upload a template them next next //it will create bucket in s3

npm i -g aws-cdk
cdk --version
mkdir cdk-starter then cd
cdk init --language=typescript
cdk bootstrap //it will create a cf stack and resources in aws
cdk deploy // it will deploy and create a CdkStarterStack in aws cf, it will create a cdk.out folder locally which includes the template
//cdk synth - it will just create the cdk.out folder
