# .\EC2InstanceCustomVPC
# Description
This Template Creates an EC2 instance in a defalut VPC

## Parameters
The list of parameters for this template:


## Resources
The list of resources this template creates:

### MainVPC 
Type: AWS::EC2::VPC  
### PublicSubnetOne 
Type: AWS::EC2::Subnet  
### PublicSubnetTwo 
Type: AWS::EC2::Subnet  
### PublicSubnetThree 
Type: AWS::EC2::Subnet  
### PrivateSubnetOne 
Type: AWS::EC2::Subnet  
### PrivateSubnetTwo 
Type: AWS::EC2::Subnet  
### PrivateSubnetThree 
Type: AWS::EC2::Subnet  
### MainGateWay 
Type: AWS::EC2::InternetGateway  
### AttachGateway 
Type: AWS::EC2::VPCGatewayAttachment  
### MainPublicRouteTable 
Type: AWS::EC2::RouteTable  
### MainPublicOne 
Type: AWS::EC2::SubnetRouteTableAssociation  
### MainPublicTwo 
Type: AWS::EC2::SubnetRouteTableAssociation  
### MainPublicThree 
Type: AWS::EC2::SubnetRouteTableAssociation  
### AllowSSHAndHTTP 
Type: AWS::EC2::SecurityGroup  
### myEC2Instance 
Type: AWS::EC2::Instance  

## Outputs
The list of outputs this template exposes:

