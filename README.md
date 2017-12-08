# Java Application Deployment,  by Ansible
This will Deploy Java App on Tomcat Server with Nginx as a Reverse Proxy Server.

# Perequisites
* ubuntu 14.04
* Ansible 2.4.0


# Bootstrap
* Add ssh key of root user to given instance.

### Update Configurations files
* Update the Inventory Files
* Update vars for Each in there respective directory like :- ``` roles/tomcat/vars/main.yml ```


```
ansible-playbook main.yml -i inventory
```

### To view Running Application
Update your hosts file with following entries.

```
* <ip address of Ubuntu 14 machine>
* tomcat.demo.com

```
