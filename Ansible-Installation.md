# Ansible Installation on Amazon Linux
## Pre-requisites:
Amazon Linux VM's

Steps to be followed are below:

1. Update pkg manager:
```
sudo yum update -y
```

2. Install the EPEL repository, which contains additional packages not included in the default Amazon Linux repository:
```
sudo amazon-linux-extras install epel
```

3. Install Ansible using the following command:
```
sudo yum install ansible -y
````

4. Once the installation is complete, you can verify the installation by checking the Ansible version:
```
ansible --version
```
