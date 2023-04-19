# terraform-module-aws
This projects has VPC,EC@, RDS, ALB, Autoscaling modules to provision them in aws.

The idea is to provision a 2-tier model in custom vpc with 2 public subnets and 2 private subnets. All 4 of them will be in 2 different zones using Terraform. 
I will also provision 2 application servers/EC2 instances in those public subnets and 
2 RDS mysql servers in private subnets along with the Application load balancer and autoscaling feature.

Please look into this for more details https://hashnode.com/draft/6436488ddbd13a000f6c4651
