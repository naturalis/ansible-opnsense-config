# Ansible Role: OPNSense config

Used in [network](https://github.com/naturalis/network/) repo.

Runnable with:
```bash
ansible-playbook playbooks/opnsense_config.yml -i environments/prod
```

## Requirements

config.xml file placed in files/

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    ..

## Dependencies

None.

## Example Playbook

    - hosts: firewall
      roles:
        - ansible-role-opnsense-config

## License

Apache2
