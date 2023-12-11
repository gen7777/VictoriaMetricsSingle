# ansible-playbooks



Install collection:

```shell
ansible-galaxy collection install victoriametrics.cluster
```

## Contents

Collection includes the following roles:


- [single](./roles/single) - installs and configures VictoriaMetrics single node
- [vmagent](./roles/vmagent) - installs and configures `vmagent`
- [vmalert](./roles/vmalert) - installs and configures `vmalert`


# Testing

I'm using vagrant and libvirt for testing purpose. visit vendors' web-site for instructions of installing program.
vagrant: https://www.vagrantup.com/downloads

Also, most roles are tested with `molecule`. Please, check out installation docs: https://ansible.readthedocs.io/projects/molecule/installation/
