Approach:
changes are made here to demostrate Jenkins-Github webhook Functionality
-Master Branch is usually the most stable branch, as Jenkins should pull only when codes are created from the Master branch 
    I used vagrant to spin up a centos 7 virtual machine
    I used Cloudformation to create AWS Resources which include a Amazon Linux EC2 Instance
    I logged into the EC2 instance using SSH
    Ansible was installed inside the EC2 instance
    I used ansible playbook to download wordpress
