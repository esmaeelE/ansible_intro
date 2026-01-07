# ansible_intro

The files in this repository are part of the demo "Intro to Ansible" article. You can find the full article [here](https://spacelift.io/blog/ansible-tutorial)

Run virtual machines

```bash
vagrant up
```

```bash
ansible -i hosts all -m ping
```

```bash
vagrant ssh-config

ansible all -i hosts --limit host2 -a "/bin/echo hello"

ansible-inventory --list
```
