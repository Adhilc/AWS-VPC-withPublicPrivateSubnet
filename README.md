# AWS-VPC-withPublicPrivateSubnet
How to create a VPC that you can use for servers in a production environment.

## ABOUT THE PROJECT:

This example demonstrate how to create a VPC that you can use for servers in a production environment.

To improve resiliency, you deploy the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. For additional security, you deploy the servers in private subnets. The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, you deploy the NAT gateway in both Availability Zones.

![alt text](https://docs.aws.amazon.com/images/vpc/latest/userguide/images/vpc-example-private-subnets.png)

### STEPS:

#### 1. LOG TO THE AWS CONSOLE.

#### 2. CREATE VPC (2 PRIVATE AND 2 PUBLIC SUBNET).

#### 3. CREATE AUTO-SCALING GROUPS.

#### 4. DEPLOY TWO SERVERS IN TWO DIFFERENT AVAILABILITY ZONES WITH IN PRIVATE SUBNET.

#### 5. CREATE A BASTION HOST.

#### 6. CREATE AN APPLICATION LOAD-BALANCER

#### 6. SERVERS CAN CONNECT TO THE INTERNET BY USING THE NAT GATEWAY

