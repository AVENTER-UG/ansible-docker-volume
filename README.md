# Ansible playbook to deploy docker-volume

This ansible playbook will roleout our docker-volume services.

## Install RBD

```bash
    ansible-playbook -i ../inventory/mesos plays/server-config.yaml --tags rbd
```

