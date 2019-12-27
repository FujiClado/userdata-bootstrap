## Ansible


```
#!/bin/bash

amazon-linux-extras install ansible2 -y
```

---

## Docker

```
#!/bin/bash

yum install docker -y
usermod -a -G docker ec2-user
service docker restart
chkconfig docker on

```
