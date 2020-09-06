## The following issues have been fixed for successful deployments
1. Uncommented line  (ERICA engineer interview task) in 010_resources.yml file
1. Added MapPublicIpOnLaunch property true in the subnet
1. Added the poloicy for EC2DescribeVolumes for EC2 InstanceRole
1. Fixed nginx installation for the AMI
1. Added the script to install the files and packages for the metadata (cfn-init)
1. Configured the environment using AWSCLI in MacOS


## Deploying in Sydney and Mumbai regions
Created two different stacks for two regions. For the AMIs and availability zones I have used the same yml templates and changed the values for the AMI and availability zones while I run the deployment. 

Here below the URLs for the two deployments

Sydney Region: http://ec2-13-210-71-180.ap-southeast-2.compute.amazonaws.com/

Mumbai Region: http://ec2-13-235-243-106.ap-south-1.compute.amazonaws.com/
