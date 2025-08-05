# How to Connect to AWS EC2
This repository contains resources referenced in the [How to Connect to EC2 series](https://youtube.com/playlist?list=PLyW_LeJHN3dd4OhrYg6X99a7adtlsiNqJ&si=SvJhwTOUqasnElgF) videos.

Series Part 1: [Connect to EC2 using RDP client](https://youtu.be/nyxTK85YXfE)  
Series Part 2: [Connect to EC2 using SSH client](https://youtu.be/MH0lOY9k5Gs)  
Series Part 3: [Connect to EC2 using Instance Connect](https://youtu.be/dBOgozollak)  
Series Part 4: [Connect to EC2 using Session Manager](https://youtu.be/5rnxBQ1zKzU)  
Series Part 5: [Connect to EC2 using Fleet Manager](https://youtu.be/umcAdFgQ0Zs)  

## Resources

- **ConnectToEC2-DemoInstanceConnectPolicy.json** - AWS IAM policy to grant IAM user to connect to EC2 using Instance Connect and Instance Connect Endpoint
- **ConnectToEC2-DemoSessionManagerUserPolicy.json** - AWS IAM policy to grant IAM user to connect to EC2 using Session Manager, Fleet Manager, EC2 connect and AWS CLI.
  - **Important** - replace the resource on first statement with your region code and AWS account number.
- **ConnectToEC2-DemoFleetManagerRDPUserPolicy.json** - AWS IAM policy to grant IAM user to connect to Windows EC2 using Fleet Manager Remote Desktop Connection
  - **Important** - replace the condition resource on SSMStartSession statement with your AWS account number.
