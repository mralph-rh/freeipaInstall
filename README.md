# Ansible playbook/role to install FreeIPA on Fedora machines
- What does this do?
This Ansible playbook will install and configure a FreeIPA lab on already provisioned machines(2 servers and 1 Client).

- What put yourself through this?
I needed the ability to create a lab environment to not only test updates on, but to spin up a demo lab.

- How long does this take to spin up?
This will tak about 20mins to install the lab.

- What environment is needed for this to work properly?
This was built using two Fedora 36 Servers and one Fedora 36 Workstation. The FreeIPA servers will be installed on the Fedora Servers and the FreeIPA client will be installed on the Fedora Workstation. You need to install the ansible-core and ansible-freeipa packages on the Fedora Workstation.

- How are the server specs?
Currently all machines are VMs used have 2 vCPUs, 4 GB RAM, and 30 GB HDD.

- What is required to run the Ansible playbook?
You only need ansible-freeipa and ansible-core to run this.

- Are there any files that need to be changed in this?
The only changes that need to be made are the variables in the inventory file.