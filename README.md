```
kubectl describe pod mysql-primary-0 -n mysql|grep -i "MYSQL_REPLICATION_MODE"
kubectl describe pod mysql-secondary-0 -n mysql|grep -i "MYSQL_REPLICATION_MODE"
```
<img width="1286" height="103" alt="image" src="https://github.com/user-attachments/assets/76fef729-27c0-4a4e-9e37-9c7ce8faa5cd" />
