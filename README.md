# Task-3: Create and Configure a Virtual Private Cloud (VPC) with Subnets
Setting Up a VPC on AWS:
Log in to the AWS Management Console.

In the search bar, type VPC and select VPC from the results.

On the VPC Dashboard, click Create VPC.

Choose VPC only or VPC and more based on your requirements: VPC only: Creates a VPC without additional resources. VPC and more: Creates a VPC along with subnets, route tables, and gateways.

Provide a Name tag for your VPC.

Specify the IPv4 CIDR block (e.g., 10.0.0.0/16) to define the IP address range.

(Optional) Enable IPv6 CIDR block if needed.

Choose the Tenancy option: Default: Instances share hardware with other AWS accounts. Dedicated: Instances run on hardware dedicated to your account.

(Optional) Add tags by entering a key-value pair.

Click Create VPC to finalize the setup.

Adding Subnets

Navigate to Subnets in the VPC Dashboard.

Click Create Subnet.

Select the VPC you just created.

Provide a Name tag, choose an Availability Zone, and specify the IPv4 CIDR block for the subnet.

Click Create Subnet.
Learn how public and private resources are separated
Gain hands-on knowledge of Internet Gateways, Route Tables, and CIDR Blocks
Build a foundation for secure deployments and hybrid cloud networking
