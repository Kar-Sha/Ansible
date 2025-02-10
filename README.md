# Ansible
HW#1 for CMPE272

## Task 
Configure two VMs, VM1 and VM2 either on your own hardware, or in a cloud environment. Configure Ansible to deploy a webserver on VM1 and VM2 on port 8080 with a web page that is accessible from a web browser, and displays the message: “Hello World from SJSU-X” where X is 1 or 2 depending on which webserver instance, VM1 or VM2.

## Files
- webserver.yml installs Apache web server and allows both VMs to be able to connect to the 8080 port.
- undeploy.yml uninstalls and removes Apache from both VMs
- inventory.ini are the two VMs I created using Microsoft Azure. They also contain the ip addresses needed for Ansible to reach the VMs.
