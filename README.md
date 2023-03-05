# Quickstart for the friesenkiwi.uberspace Ansible Collection

This example shows how to use [friesenkiwi.uberspace](https://galaxy.ansible.com/friesenkiwi/uberspace) in your own playbooks.

It serves as a quickstart to new users.

Please make sure to study the [uberspace_account README](https://github.com/friesenkiwi/ansible-collection-uberspace/tree/master/roles/uberspace_account) and to understand what is happening behind the scenes, because you are responsible for the effects.

## Running this example

```bash
ansible-galaxy collection install -r requirements.yml
ansible-playbook -i account-inventory hello-world-goodbye.yml
```
