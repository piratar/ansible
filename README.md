# Ansible for Piratar

FYI: The key file group_vars/piratar with all the secret variables is missing for obvious reasons.

### Setup

1. Install the missing roles (which are git ignored)

  `ansible-galaxy install -r requirements.yml`

2. Ping all the servers to see which ones you have access to

  `ansible -m ping all`

3. Read more about ansible!


4. Run a playbook:

```
ansible-playbook docker1.piratar.is.yml
```
