# Windows EC2 Ansible Execution Environment

[Ansible Builder](https://github.com/ansible/ansible-builder) config to create an Ansible Docker image with dependencies for targeting Windows EC2 instances

Adds:

- AWS collections from Galaxy
- Windows collections from Galaxy
- Python libraries for connecting to WinRM over a SOCKS proxy
- Session Manager plugin for connecting to hosts over AWS SSM
