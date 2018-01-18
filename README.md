Ansible Role: kubernetes kubectl conf
=========

Configure [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) on local machine after kubernetes cluster created.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: all
  become: yes
  roles:
    - { role: djx339.k8s-kubeadm-kubectl-conf }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
