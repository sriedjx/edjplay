# edjplaybooks
###### EDJX Ansible Playbooks <br>
update target nodes ip's inside inventory file under group_names bas below<br>
group_names should be as below
```
[writer]
*.*.*.*
[bootstrap]
*.*.*.*
[runtime]
*.*.*.*
```

then run
```ansible-playbook role.yaml -e "username=$username password=$password"```
