\# Project 1C — EC2 Web Server in Custom VPC



\## What I Built

Launched an Amazon EC2 instance inside the custom VPC,

installed Apache web server, and served a live webpage

accessible via public IP address.



\## Resources Created



| Resource | Value |

|---|---|

| Instance Name | indira-web-server |

| AMI | Amazon Linux 2023 |

| Instance Type | t2.micro (Free Tier) |

| VPC | indira-project-vpc |

| Subnet | indira-public-subnet (us-east-1a) |

| Security Group | indira-web-sg |

| Ports Open | 22 (SSH), 80 (HTTP) |



\## Security Group Rules

| Type | Port | Source | Purpose |

|---|---|---|---|

| SSH | 22 | 0.0.0.0/0 | Server access |

| HTTP | 80 | 0.0.0.0/0 | Web traffic |



\## Commands Run on Server

```bash

sudo yum update -y

sudo yum install httpd -y

sudo systemctl start httpd

sudo systemctl enable httpd

echo "<h1>Hello from EC2!</h1>" | sudo tee /var/www/html/index.html

sudo systemctl status httpd

```



\## Key Concepts Learned

\- EC2 = Virtual server in the cloud

\- AMI = Operating system template

\- Security Groups = Firewall rules for EC2

\- Key Pairs = Secure SSH access

\- Public IP assigned because instance is in public subnet

\- Apache httpd = web server software



\## Result

Live webpage accessible at: http://\[Public-IPv4-Address]

