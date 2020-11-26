# edjplaybooks
###### EDJX Ansible Playbooks <br>
update target nodes ip's inside inventory file under group_names as below<br>
```
>[writer]
*.*.*.*
>[bootstrap]
*.*.*.*
>[runtime]
*.*.*.*
```

then run
```ansible-playbook role.yaml -e "username=$username password=$password"```
