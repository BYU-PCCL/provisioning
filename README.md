# provisioning

> Ansible playbooks for provisioning BYU PCCL machines

## requirements

[Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html)

## usage

```
ansible-playbook bootstrap.yml --inventory=hosts --ask-pass --ask-become-pass
```

As always, check the output of `--help` for more options; the
`--limit`, `--tags`, and `--extra-vars` flags are particularly useful.

If you already have SSH keys setup or after you run [`ssh.yml`](./ssh.yml) (or [`bootstrap.yml`](./bootstrap.yml)), you can omit the `--ask-pass` option.
