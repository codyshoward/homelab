# HomeLab
Functional Projects:
1. awx-operator-builder: Builds out K3S/AWX operator.
     Prereqs: Centos 9 Server (no gui) and destination host must be able to resovle its hostname and fqdn.
     If running locally, be sure to move template files for playbook to use.
     After playbook has ran, login to host and run "dockectl get svc -n awx" and allow the port number through the host firewall.
     Dont turn the firewall off, it's needed for masquerading. 
