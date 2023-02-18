#Using Terraform for automated provisioning of AWS resources

The intention was to use Terraform to deploy AWS resources: VPC, Route Table, Internet Gateway, Security Group, with proper associations from the get-go and an EC2 instance inside a pre-made subnet that has pre-installed softwares like Docker (using a "userdata template"), so it spins up in a ready-to-go state