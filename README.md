# cloudformation
CloudFormation samples presented at the Louisville AWS User Group meeting on 06/30/2016.

The templates provide simplified overview of CloudFormation for users not familiar with CloudFormation.

simple-stack.json => over simplified sample on how to deploy a single EC2 resource in a us-east.

simple-stack-userdata.json => builds on the previous example and includes passing UserData to bootstrap an EC2.

ref-web-stack-east.json => full parameterized stack that includes auto-scaling group, elastic load balancer running Amazon linux AMI. 

The reference stack could be used as a foundation for customers running in us-east but should be tailored to meet requirements.

