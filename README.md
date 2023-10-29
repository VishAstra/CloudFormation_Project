# CloudFormation Template for Creating AWS Resources

This CloudFormation template automates the creation of AWS resources, including a VPC with public and private subnets, EC2 instances, security groups, and an S3 bucket. 

## Prerequisites

Before using this CloudFormation template, you should have the following:

1. An AWS account.
2. AWS Command Line Interface (CLI) installed.
3. A valid EC2 key pair for SSH access.

## Usage

Follow these steps to create the AWS resources using this CloudFormation template:

1. **Upload the CloudFormation Template:**

   - Log in to the AWS Management Console.
   - Navigate to the CloudFormation service.

   - Click "Create stack" and choose "With new resources."
   - Select "Upload a template file" and choose the YAML file provided in this repository.!
   - Click "Next" to proceed.
     ![1](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/275777ea-d09e-40e2-984a-f267c6e6a7f1)
  ![2](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/0df2910c-76cf-4b59-bed3-bc0897a4b052)




   - Click "Next" to proceed.
   

2. **Create Stack:**

   - Review the configuration, and click "Next."

   - Acknowledge the AWS CloudFormation terms and click "Create stack."

   - Wait for the stack creation to complete. This may take a few minutes.
   ![3](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/d7896d2f-f3ae-4ebd-8983-de9ec0a574af)



3. **Accessing Resources:**

   - Once the stack is created, you will find details about the created resources in the CloudFormation stack outputs.

   - You can find the details of the public and private subnets, EC2 instances, security groups, and the S3 bucket.
  ## VPC, Subnetes, Route table, Internet Gateway 👇
   ![4](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/52329a58-7ad3-4687-8d7b-582ca4442648)
![5](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/7ba21432-57b4-4cdc-bb9d-2eed9057937f)
![6](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/e9287998-ed7e-4a89-90e5-3fffce7a3643)
![7png](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/bf3b42aa-30e7-4645-b86d-10e8bbeb09cf)
  ## Instance 👇
![7](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/cff8585c-a9c8-4feb-832b-c7dde613ca64)
 ## Security Group 👇
![9](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/f6b16405-50cd-4593-a268-339abf538910)
 ## S3 bucket👇
![10](https://github.com/INFOTRIXS/10-Infrastructure-as-Code/assets/122463168/1bd44130-076a-4879-9822-54f170274f3f)
