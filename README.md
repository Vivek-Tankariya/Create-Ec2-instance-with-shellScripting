#AWS CLI EC2 Instance Creation Script
This Bash script automates the process of installing the AWS CLI, creating an EC2 instance, and configuring it. It includes functions for checking AWS CLI installation, installing AWS CLI v2, waiting for an EC2 instance to be in the running state, creating an EC2 instance, and configuring AWS credentials.

#Usage
Check AWS CLI:

1.The script checks if the AWS CLI is installed. If not, it installs it first.
Install AWS CLI:

2.Downloads and installs AWS CLI v2 on Linux.
Verifies the installation.
Cleans up the temporary files.
Wait for Instance:

3.Waits for an EC2 instance to be in the running state.
Create EC2 Instance:

4.Accepts parameters such as AMI ID, instance type, key name, subnet ID, security group IDs, and instance name.
Uses the AWS CLI to create an EC2 instance with the specified configuration.
Tags the instance with a name.
Configure AWS:

5.Configures AWS credentials if the AWS CLI is installed for the first time.

###Usage Example - ./script.sh <AMI_ID> <INSTANCE_TYPE> <KEY_NAME> <SUBNET_ID> <SECURITY_GROUP_IDS> <INSTANCE_NAME>
Replace <...> with your actual values.

Requirements
Bash shell
AWS CLI v2
Internet connection for downloading AWS CLI
