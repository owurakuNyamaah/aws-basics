# AWS Notes

## Cloud & DevOps
- Cloud: on-demand computing resources in remote data centers
- DevOps: automates deployment, monitoring, and scaling

## AWS Global Infrastructure
- Region: physical location (e.g., eu-west-2 London)
- Availability Zone (AZ): isolated data center within a region
- High availability = multiple AZs

## IAM
- Users: represent people/systems
- Roles: temporary permissions for services
- Policies: define allowed/denied actions
- Principle of Least Privilege: only give needed permissions

## EC2
- Virtual server running Linux or Windows
- t2.micro/t3.micro = Free Tier
- SSH into server using key pair
- Security groups = firewall rules

## S3
- Stores static assets (HTML, images, CSS)
- Can host static websites
- Files served via public URL or EC2

## VPC
- Virtual private network
- Public subnet → EC2 with internet access
- Private subnet → internal services (databases)
