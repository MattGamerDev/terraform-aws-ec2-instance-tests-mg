# terraform-aws-ec2-instance-tests-mg

A Terraform module for creating EC2 instances with integration tests.

## Usage

module "ec2_instances" {
  source = "app.terraform.io/YOUR_ORG/ec2-instance-tests-mg/aws"
  
  instance_count = 2
  instance_type  = "t2.micro"
}