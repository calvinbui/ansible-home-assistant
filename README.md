[![Build Status](https://travis-ci.com/calvinbui/ansible-home-assistant.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-home-assistant)
![GitHub release](https://img.shields.io/github/release/calvinbui/ansible-home-assistant.svg)
![Ansible Quality Score](https://img.shields.io/ansible/quality/40535.svg)
![Ansible Role](https://img.shields.io/ansible/role/d/40535.svg)

# Ansible Home Assistant

Home Assistant in Docker

##  Requirements

N/A

## Role Variables

`home_assistant_name`: Name of container

`home_assistant_image`: Docker image to  use

`home_assistant_config_directory`: Directory to store configuration files

`home_assistant_environment_variables`: Docker environmental variables

`home_assistant_docker_additional_options`: [Additional parameters](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) to add to docker container

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
   - role: calvinbui.ansible_home_assistant
```

## License

GPLv3

## Author Information

http://calvin.me
