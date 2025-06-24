# EC2-AMI-Creation-Elastic-Ip-address
This Repo contains Steps to create an ami image for ec2 instance and reuse that to create an ec2 instance and steps to create elastic ip address and attach to ec2
![1](https://github.com/user-attachments/assets/79d7945e-c5a9-4e1e-96d8-214613bb8bc3)
# Select the instane and go to image and templates and click create image
![2](https://github.com/user-attachments/assets/3055a93f-771f-4ad4-aa2c-18b51cc79184)
# Give a name to the image
![3](https://github.com/user-attachments/assets/04495a45-8c38-4622-81b9-be5605159cfe)
# Wait for the ami to get in the available state
![4](https://github.com/user-attachments/assets/e5e368b5-dd38-4170-8de8-73b69cae654a)
# Now select the image and click launch instance from ami
![5](https://github.com/user-attachments/assets/26058553-5baf-4db2-8333-3cf174e83e26)
![6](https://github.com/user-attachments/assets/d9e2d8c3-a412-4b9d-b7c0-fb4f0503bbc7)
# Select the subnet,vpc,security group 
![7](https://github.com/user-attachments/assets/a942fd94-a685-4354-8a57-8098b60e1e69)
![8](https://github.com/user-attachments/assets/bdcec609-ff6a-4f20-83ba-2db706f4ba5c)
# In the previous instance i have deployed node.js application by using same ami i created a instance all the softwares, current running processes will be as it is in newly created instance with that ami




# Elastic Ip address ( How to allocate to ec2 )
![Screenshot (410)](https://github.com/user-attachments/assets/34cbe3fa-e28b-4f03-9c45-de2e57801390)
# Go to ec2 and click elastic ips
![Screenshot (411)](https://github.com/user-attachments/assets/551860a8-d67b-4735-a4e7-1c21f93dbfbc)
# Once see the settings and click allocate button
![Screenshot (412)](https://github.com/user-attachments/assets/cca898d7-4399-4ac9-af2b-f1536e6e6a77)
# It has been created and the ip address can be seen in the picture
![Screenshot (413)](https://github.com/user-attachments/assets/c057ad34-45b1-47aa-b29d-20df2c7c32ed)
# Now select elastic ip and goto actions and click Assoicate elastic ip address
![Screenshot (414)](https://github.com/user-attachments/assets/0f1ee34c-bb56-443f-9c3e-de82da57ae74)
# Select the instance in which you want to allocate the elastic ip address
If click this to be reassociated is selected then it will automatically detach and attach to new instance if elastic ip is allatching to another ec2 when it is already reattached 
![Screenshot (415)](https://github.com/user-attachments/assets/26b98374-6e32-40a0-8da9-a1af92f5a7e1)
# We can see in the picture that elastic ip address has been allocated to the ec2 instance
