# CICD_Deployment

CI/CD Deployment Using Ansible CM Tool

Assumptions: 
A. Create an EC2 instance and open SG for ssh and 8080.
B. On the EC2 instance, install all necessary tools.
C. Run the playbook in this repo to achieve Step1.

STEP 1: Configure Jenkins server as Ansible provisioning machine - DONE
STEP 2: Install Ansible plugins in Jenkins CI server - DONE
    Step 2: Install Git on Ec2 instance - DONE
    Setp 3: Install Ansible plugins in Jenkins CI server - DONE
    Step 4: Install Github plugin in Jenkins CI server - DONE

          4a. Sample hello world was forked from - https://github.com/srinivasmdas/hello-world?organization=srinivasmdas&organization=srinivasmdas
          4b. Configure a Job to  pull the sample helloworld code.
          4c. SetuP maven on Jenkins and Setup Env variables
          4d. Install Maven Plugin on Jenkins UI.
          4e. Configure Maven and Java- Screenshot Above.
          4f. Build sample java project using Jenkins
          4g. Maven build of sample project is SUCCESS
          
STEP 3: Prepare Ansible playbook to run Maven build on Jenkins CI server
        
    3a. Create docker image
    3b. copy image to docker hub
    3c. Jenkins job to build an image onto ansible
    
    ABOVE STEPS ARE ACCOMPLISHED BY BUILD.YML
 

STEP 4: Prepare Ansible playbook to execute deployment steps on the remote web container with restart of the web container post deployment
    4a.   deploy Image using Ansible Playbook

ABOVE STEP IS ACCOMPLISHED BY DEPLOY.YML





