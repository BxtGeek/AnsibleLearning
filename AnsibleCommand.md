## Command to update the yum based system
```
ansible all -m yum -a "name=* state=latest"

ansible all -m shell -a "yum update && yum upgrade -y"
```