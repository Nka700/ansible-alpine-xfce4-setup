
before run this playbook, run this command.
```bash
apk add ansible
```

then run playbook.  
```bash
ansible-playbook -i localhost main.yml --extra-vars "username=${Your user name} upassword=${Your Password}"
```
