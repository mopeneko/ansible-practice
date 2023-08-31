# ansible-practice

## Prerequisite

- OS: Ubuntu 22.04.2 LTS
- You need to create an user for Ansible
- You need to put a public key for SSH
- You need to grant `NOPASSWD` for the user

## Requirements

- [Poetry](https://github.com/python-poetry/poetry)
- [Direnv](https://github.com/direnv/direnv)

## Usage

### Set up environment

```sh
poetry install
direnv allow
```

### Run Ansible Playbook

```sh
ansible-playbook -i hosts site.yml
```
