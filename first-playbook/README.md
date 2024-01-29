# Ansible

**Definition:** It is a tool that helps you to automate different IT tasks. It is a versatile automation tool that acts as your guiding force in managing your cloud environment. It is used for configuration management, application deployment, and Infrastructure provisioning. 
                
-> Ansible is commonly used in the cloud for managing virtual machines and containers, automating provisioning, configuration, and orchestration.
 
-> Ansible simplifies infrastructure management by automating tasks and reducing manual intervention.

-> An Ansible playbook is a YAML file that describes a series of tasks to be executed by Ansible. Playbooks define the desired state of the system by specifying tasks, modules, variables, and other configurations.

-> A playbook is an Ansible script that executes tasks on managed nodes. Playbooks are written in YAML format and define a set of tasks and configurations to be applied to managed nodes. They orchestrate Ansible's actions, enabling you to define complex workflows and automate tasks across your infrastructure.


 **Ansible components:**
 
**Control Node:** This is where Ansible is installed and run from. It's the central point from which configuration management, application deployment, task execution, and orchestration are handled. It does not require any agent software to be installed on any managed nodes. 

**Managed nodes/ Hosts:** These are the servers (or machines) that are managed by Ansible. They can be any type of host, provided Ansible has a way to communicate with them. 

**Inventory:**  It is a list of managed nodes that Ansible can interact with. The inventory file specifies the IP addresses or domain names of the machines you want to manage, along with optional configuration information such as the remote user, SSH port, and any groupings of hosts.

**Modules:** Modules are units of code that Ansible executes. Each module is designed to accomplish a specific task, like installing a package, copying files, or creating a cloud infrastructure resource. 

**PlayBook:** Playbooks are the heart of Ansible's configuration, deployment, and orchestration language. Written in YAML, playbooks are a series of 'plays' that define the work to be done on managed nodes (hosts).

**Plugins:** They control how you connect to a managed node, manipulate data, and even control what is displayed in the console. 

