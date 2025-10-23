# Task-3-Create-and-Configure-a-Virtual-Private-Cloud-VPC-with-Subnets
Learn how cloud networking works by creating a Virtual Private Cloud (VPC) with both public and private subnets, enabling controlled internet access. This task focuses on understanding secure cloud architecture—how resources are segmented, isolated, and protected within the cloud environment.

Deliverables
✅ Screenshot of VPC Dashboard showing created subnets
✅ Screenshot of Route Table configuration
✅ Short Description including:
CIDR range
Number of subnets
Region
Internet access status
🧭 Step-by-Step Guide
1️⃣ Login to AWS Console
Go to AWS Management Console
Navigate to VPC Dashboard
2️⃣ Create a Virtual Private Cloud
Click Create VPC
Select VPC only option
Set IPv4 CIDR block: 10.0.0.0/16
(Defines the address range for your private network)
3️⃣ Create Subnets
Public Subnet
CIDR Block: 10.0.1.0/24
Enable Auto-assign public IPv4 address
Private Subnet
CIDR Block: 10.0.2.0/24
Disable Auto-assign public IPv4 address
4️⃣ Create and Attach an Internet Gateway (IGW)
Navigate to Internet Gateways → Create Internet Gateway
Attach it to your VPC
(This enables internet access for the public subnet)
5️⃣ Configure Route Tables
Public Route Table
Add Route: 0.0.0.0/0 → Internet Gateway (IGW)
Associate with Public Subnet
Private Route Table
Keep default routes (no internet access)
Associate with Private Subnet
6️⃣ Verify Configuration



Go to VPC → Subnets and confirm:

Public subnet has internet access
Private subnet is isolated (no direct internet access)
7️⃣ Save and Document



Include in your repository:

Screenshot of VPC Dashboard
Screenshot of Route Tables
Short note including:
VPC Name: (e.g., MyVPC)
CIDR Block: 10.0.0.0/16
Public Subnet: 10.0.1.0/24
Private Subnet: 10.0.2.0/24
Region: (e.g., us-east-1)
Internet Access: Enabled for Public Subnet only
💡 Outcome



By completing this task, you will:

Understand VPC architecture and subnet segmentation
Learn how public and private resources are separated
Gain hands-on knowledge of Internet Gateways, Route Tables, and CIDR Blocks
Build a foundation for secure deployments and hybrid cloud networking
