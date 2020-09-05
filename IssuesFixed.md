## The following issues have been fixed for successful deployments
1. Uncommented line  (ERICA engineer interview task)
1. Added MapPublicIpOnLaunch property true in the subnet
1. Added EC2DescribeVolumes for EC2 InstanceRole
1. nginx installation for the AMI
1. Added the script to install the files and packages for the metadata (cfn-init)
1. Used AWSCLI on Mac for configuring the environment


## Deploying in Sydney and Mumbai regions
Created two different stacks for two regions. For the AMIs and availability zones I have used the same yml templates and changed the values for the AMI and availability zones while I run the deployment. 

Here below the URLs for the two deployments

Sydney Region: http://ec2-3-25-189-212.ap-southeast-2.compute.amazonaws.com/

Mumbai Region: http://ec2-13-233-198-200.ap-south-1.compute.amazonaws.com/
