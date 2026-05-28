\# Project 1B — VPC with Public and Private Subnets



\## Architecture Overview

Custom AWS VPC built from scratch with isolated 

public and private subnets across two Availability Zones.



\## Resources Created



| Resource | Name | Value |

|---|---|---|

| VPC | indira-project-vpc | 10.0.0.0/16 |

| Public Subnet | indira-public-subnet | 10.0.1.0/24 — us-east-1a |

| Private Subnet | indira-private-subnet | 10.0.2.0/24 — us-east-1b |

| Internet Gateway | indira-igw | Attached to VPC |

| Route Table | indira-public-rt | Routes 0.0.0.0/0 to IGW |



\## Architecture Diagram

