```
kubectl describe pod mysql-primary-0 -n mysql|grep -i "MYSQL_REPLICATION_MODE"
kubectl describe pod mysql-secondary-0 -n mysql|grep -i "MYSQL_REPLICATION_MODE"
```
<img width="1286" height="103" alt="image" src="https://github.com/user-attachments/assets/c11f5268-eab2-4d2d-8dac-2f99f74ed3d5" />
