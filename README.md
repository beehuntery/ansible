## Usage
```bash
pip install ansible

git clone https://github.com/beehuntery/ansible.git

cd ansible
ansible-playbook -i hosts.yml site.yml
```


## Roles
| Role    | Description                                      | OS     |
|---------|--------------------------------------------------|--------|
| docker  | Setup Docker engine and can use as non-root user | Ubuntu |
| aws-cli | Install AWS CLI                                  | Ubuntu |
