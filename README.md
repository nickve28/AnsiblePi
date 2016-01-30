**A simple ansible playbook for configuring a new pi instance (made for raspbian)**

**Running the playbook**

In order to run the playbook, the following requirements have to be met:

1. Ansible must be installed on your machine
2. An SSH connection must be established between your machine and the Pi, also allowing passwordless authentication. I won't go in detail about this here.
3. Your Pi must be added to /etc/ansible/hosts (with the appropriate role) An example entry could be:
4. [raspiserver]
5. <IP-ADDRESS><:PORT (optional)>

Run the shell script to execute
