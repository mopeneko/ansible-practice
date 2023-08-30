# ansible-practice

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
