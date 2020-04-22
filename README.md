# ansible-k8s-setup
This will setup a kubernetes cluster on Centos7 machines using ansible.
You need these machines:
1. Ansible controller - controller.example.com - 10.0.0.99 - 1 vcpu / 2 gib ram
2. Kubernetes Master - master.example.com - 10.0.0.100 - 2 vcpu / 4 gib ram
3. Kubernetes Node1 - nodeone.example.com - 10.0.0.1 - 1 vcpu / 4 gib ram
4. Kubernetes Node2 - nodetwo.example.com - 10.0.0.2 - 1 vcpu / 4 gib ram

If you can allocate more compute resources, its better
If you change your machine IP's then you have to change those whereever
those were referred.

