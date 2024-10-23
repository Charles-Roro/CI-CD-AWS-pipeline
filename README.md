# CI-CD-AWS-pipeline
A CI/CD pipeline using Jenkins, SonarQube, Nexus, and Snyk

Creating 2 VMs in AWS to host the SonarQube and Nexus instances

Selecting Ubuntu as the OS and alloting enough memory for the Nexus instance (4GB)
![Screenshot 2024-10-23 at 10 39 54 AM](https://github.com/user-attachments/assets/362b3084-97f2-4bf9-bd27-d93a48952633)
![Screenshot 2024-10-23 at 10 42 03 AM](https://github.com/user-attachments/assets/8c779ab0-6026-44b2-8d2e-f74785a56723)

Custom made VPC and security group to ensure security of the environment
![Screenshot 2024-10-23 at 10 43 34 AM](https://github.com/user-attachments/assets/8fccb6fd-8570-45b4-bce3-543937d18d31)

Using Docker as the Host for the Jenkins instance
![Screenshot 2024-10-23 at 10 46 51 AM](https://github.com/user-attachments/assets/054c4020-e9ff-4a9e-9ac7-0e82d94c75cb)
![Screenshot 2024-10-23 at 10 55 19 AM](https://github.com/user-attachments/assets/ba830b9a-720e-4611-9701-4527e557a497)

Updating SonarQube Ubuntu instance
![Screenshot 2024-10-23 at 11 00 54 AM](https://github.com/user-attachments/assets/d8354501-70d8-44cd-a3bb-389f819dd8cc)
Installing Docker on the SonarQube instance
![Screenshot 2024-10-23 at 11 05 36 AM](https://github.com/user-attachments/assets/105939c7-c631-4315-9e36-1537bf5cadac)
Pulling docker image for SonarQube on to the instance
![Screenshot 2024-10-23 at 11 27 32 AM](https://github.com/user-attachments/assets/946ad2dd-dc21-4753-8c71-8b9057ae44dd)

SonarQube is up and running(password and username MUST be changed from default!).
![Screenshot 2024-10-23 at 11 36 25 AM](https://github.com/user-attachments/assets/e9b8f0e3-ccda-4416-b4ce-51991dc0bed2)


Updating Nexus Ubuntu instance
![Screenshot 2024-10-23 at 11 51 16 AM](https://github.com/user-attachments/assets/5d3e82de-5c46-4e78-bfd7-828e4e22a9a3)
Installing Docker on the Nexus instance
![Screenshot 2024-10-23 at 11 54 38 AM](https://github.com/user-attachments/assets/be9fe545-0533-4d2e-8804-023ab14cec87)
![Screenshot 2024-10-23 at 11 54 52 AM](https://github.com/user-attachments/assets/a9a3664e-d5ad-4e9e-a868-7f4627907518)
Pulling Nexus docker image
![Screenshot 2024-10-23 at 11 58 09 AM](https://github.com/user-attachments/assets/0fb8534b-5fb4-427a-87cc-be3b7ca40d41)
![Screenshot 2024-10-23 at 12 01 32 PM](https://github.com/user-attachments/assets/ec6122f7-ca29-42fa-ae16-1c490ee0d946)
Getting access to the docker container information to get and change the password for Nexus
![Screenshot 2024-10-23 at 12 03 52 PM](https://github.com/user-attachments/assets/154e2747-743a-40ad-865e-b090edb85997)
![Screenshot 2024-10-23 at 12 05 47 PM](https://github.com/user-attachments/assets/d16746af-2987-48b0-80d5-08e5a0a790e2)
![Screenshot 2024-10-23 at 12 07 04 PM](https://github.com/user-attachments/assets/da2bbb40-e17f-4774-a303-0cc33d5a8a2a)




































