# .\EC2InstanceWithSG
# Description
This Template Creates an EC2 instance in a defalut VPC

## Parameters
The list of parameters for this template:

### InstanceTypeParameter 
Type: String 
Default: t2.micro 
Description: Choose the type of the Instance 
### SecurityGroupForSSHAndHTTP 
Type: AWS::EC2::SecurityGroup::Id  
Description: Select the Security Group for the Instance 

## Resources
The list of resources this template creates:

### myEC2Instance 
Type: AWS::EC2::Instance  

## Outputs
The list of outputs this template exposes:

### EC2InstaceOutput 
Description: The Public IP Address of the instance 
Export name: {'Fn::Sub': '${AWS::StackName}'}  

