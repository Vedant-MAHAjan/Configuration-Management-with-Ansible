# Database-configuration-with-Ansible
Configure MySQL database on Linux target machines using Ansible playbooks

1. When creating the ec2 instance for target machines, create a new key pair
2. Download and copy this key pair from the local machine to the control machine
3. This key will be used to ssh into the target machines
4. 


Files in the directory

![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/5850322a-e580-437b-be5a-8d55539fa92e)



Output

![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/d7a50350-6f7e-48db-a3ee-6eeedb450b0e)

![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/cdaa8bd3-8ef8-47d4-a161-b8bf8bf4aa5f)

Web output

![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/2decdab9-4b75-4c90-96ab-8ed874b05108)

DB output

Socket files are used to connect processes

![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/97998e73-1b84-4c76-a749-ef5d15eda184)


Let's check the file we copied to the target

![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/17c779fe-46cf-4260-bc22-831208ea1914)


![image](https://github.com/Vedant-MAHAjan/Database-configuration-with-Ansible/assets/88843623/134a4316-1822-44eb-9613-9635bbed02ed)





Gathering facts means Ansible is collecting information on the target machines
This helps it to compare the current state to the desired state
If state difference exists, Ansible will apply the new changes to the target machines
